# Trabajo Práctico 1 - Control de Acceso (2025)

Proyecto de Modelado y Diseño de Software.  
Se modela un sistema de **control de acceso** aplicando casos de uso, diagramas de actividades y secuencia.

## Contenido
- `tp/act-acceso.puml|png|pdf`: Diagrama de actividades del acceso.
- `tp/cu-acceso.puml|png|pdf`: Diagrama de caso de uso del acceso.
- `tp/seq-acceso.puml|png|pdf`: Diagrama de secuencia del acceso.
- `tp/README.md`: Explicación de reglas de negocio, riesgos, mitigaciones y supuestos.
- `TP-30-09.zip`: Paquete con todos los archivos del trabajo.

## Reglas de Negocio (RBAC)
- Acceso según rol (Administrador, Usuario, Invitado).
- Sesiones con token de 24h.
- Reenvío de confirmación habilitado.

## Riesgos y mitigaciones
- **Errores de consistencia**: se controlan alineando diagramas.
- **Seguridad**: no almacenar contraseñas en texto plano, usar hash y caducidad.

## Autores
- José Guari
