---
config:
  look: neo
  theme: redux
title: GA2-220501093-AA2-EV01 - Diagrama de Dominio UML
---
classDiagram
direction LR

namespace AccesoIdentidad {
    class Usuario {
        correo
        telefono
        rol
    }

    class TokenOTP {
        codigo
        expiracion
    }
}

namespace GestionReportes {
    class Reporte {
        id
        fecha
        descripcion
        estado
    }

    class Ubicacion {
        latitud
        longitud
    }

    class Evidencia {
        foto
        fecha
    }
}

namespace Notificaciones {
    class Notificacion {
        mensaje
        canal
    }

    class RegistroNotificacion {
        fechaEnvio
        estado
    }
}

Usuario "1" --> "0..*" TokenOTP : genera
Usuario "1" --> "0..*" Reporte : crea

Reporte "1" *-- "1" Ubicacion : contiene
Reporte "1" *-- "0..*" Evidencia : contiene

Usuario "1" --> "0..*" Notificacion : recibe
Notificacion --> Reporte : sobre
Notificacion "1" *-- "0..*" RegistroNotificacion : registra
RegistroNotificacion --> Usuario : destinatario