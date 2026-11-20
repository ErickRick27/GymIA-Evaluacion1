# GymIA — Interfaz de Usuario (Evaluación Sumativa N°1)

Proyecto Android nativo con layouts XML escritos a mano y Material 3 (modo claro y modo oscuro) para la gestión de rutinas de gimnasio con asistencia de IA.

## Pantallas incluidas (Actividad N°1)

1. `LoginActivity` (`activity_login.xml`): Logo, título de la app, correo, contraseña (`textPassword`) y botones de ingreso/registro.
2. `RegistroActivity` (`activity_registro.xml`): Nombre de atleta, correo, doble contraseña (`textPassword`), selección de objetivo (`RadioGroup`), aceptación de términos (`CheckBox`) y botón de registro.
3. `ListaRutinasActivity` (`activity_lista_rutinas.xml`): Barra superior con acciones y `ScrollView` con tres tarjetas de sesiones de ejemplo.
4. `AgregarRutinaActivity` (`activity_agregar_rutina.xml`): Formulario de nueva sesión (grupo muscular, ejercicio, series, repeticiones, peso en kg y notas).
5. `DetalleRutinaActivity` (`activity_detalle_rutina.xml`): Detalle completo de una rutina y botones de acción (marcar como completada, editar y eliminar).
6. `IaRutinaActivity` (`activity_ia_rutina.xml`): Campo de consulta para el entrenador IA, botón de envío y área de respuesta con ejemplo de rutina generada.
