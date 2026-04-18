---
config:
  look: neo
  theme: redux
  layout: dagre
title: GA2-220501093-AA2-EV01 - Modelo de Dominio
id: 14d2febb-4a28-44a0-8bcc-a4832ded8be5
---
classDiagram
direction TB
	namespace Institucional {
        class Usuario {
	        id
	        nombre
        }

        class Rol {
	        nombre
        }

        class Organismo {
	        nombre
        }

	}
	namespace AccesoIdentidad {
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

        class Contacto {
	        tipo
	        valor
	        autorizadoNotificacion
        }

        class HistorialReporte {
	        fecha
	        estadoAnterior
	        estadoNuevo
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

    Usuario "1" --> "1" Rol : tiene
    Usuario "1" --> "1" Organismo : pertenece
    Reporte "1" --> "0..1" Contacto : tiene
    Reporte "1" --> "0..*" TokenOTP : valida
    Reporte "1" *-- "1" Ubicacion : contiene
    Reporte "1" *-- "0..*" Evidencia : contiene
    HistorialReporte --> Reporte
    HistorialReporte --> Usuario : realizado_por
    Notificacion --> Reporte : sobre
    Notificacion "1" *-- "0..*" RegistroNotificacion : registra
    RegistroNotificacion --> Contacto : destinatario