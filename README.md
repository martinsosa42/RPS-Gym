<h1 align="center">RPS Gym</h1>

<p align="center">
  <strong>Tu gimnasio, sin planillas.</strong><br>
  Reservas de turnos con cupo, lista de espera, asistencia, cuotas y reportes, para socios, recepción, profesores y
  dueños, en la compu y en el celular.
</p>

<p align="center">
  <a href="https://rps-gym-software-system-1.onrender.com/login"><strong>→ Probar RPS Gym</strong></a>
</p>

<p align="center">
  <img src="assets/screenshots/pc/cliente-horarios.png" alt="Grilla semanal de horarios con el cupo libre de cada clase" width="820">
</p>

> Trabajo Práctico Integrador de Ingeniería de Software I (UNER), en grupo. Partimos de una especificación de requerimientos
> (IEEE 830) con 26 requerimientos funcionales y 22 no funcionales, y la llevamos a un sistema completo y desplegado.

## Cuentas de prueba

Contraseña de todas: `Gym12345`. También se puede entrar con el DNI.

| Perfil         | Usuario                       | Qué podés ver                                        |
| -------------- | ----------------------------- | ---------------------------------------------------- |
| Cliente        | `cliente1@rpsgym.local`       | Reservar, mis reservas, lista de espera, avisos      |
| Administrativo | `administrativo@rpsgym.local` | Panel del día, clientes, cuotas, horarios, asistencia |
| Profesor       | `profesor1@rpsgym.local`      | Mis clases y nómina para tomar asistencia            |
| Dueño          | `dueno@rpsgym.local`          | Reportes con descarga en PDF y Excel                 |

## Para el cliente: reservar en tres toques

Elegís la actividad, ves la semana con el cupo libre de cada horario y confirmás. El sistema controla en el momento
que haya lugar, que no te pases de las clases semanales de tu plan y que tengas la cuota al día. Si dos personas
quieren el último lugar a la vez, sólo una se lo lleva.

<p align="center">
  <img src="assets/screenshots/pc/cliente-actividades.png" alt="Elegir una actividad" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/cliente-confirmar.png" alt="Confirmar la reserva" width="400">
</p>

- **Estados claros**: cupo disponible, pocos cupos o sin cupo, con el número de lugares libres y una ayuda que
  explica cada uno.
- **Lista de espera**: si la clase está llena te anotás y te avisan cuando se libera un lugar; tenés un plazo para
  confirmarlo antes de que pase al siguiente.
- **Cancelación** hasta 2 horas antes, liberando el lugar para otro.
- **Intercambio de turnos** entre socios: proponés cambiar tu clase por la de otro y, si acepta, se reasignan las dos.
- **Avisos** dentro de la app y por correo: reserva confirmada, lugar liberado, recordatorio 24 h antes.

<p align="center">
  <img src="assets/screenshots/pc/cliente-ayuda-estados.png" alt="Qué significa cada estado del cupo" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/cliente-lista-espera.png" alt="Anotado en la lista de espera" width="400">
</p>

<p align="center">
  <img src="assets/screenshots/pc/cliente-inicio.png" alt="Inicio del cliente" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/cliente-mis-reservas.png" alt="Mis reservas" width="400">
</p>

¿No sos socio? Te registrás solo, elegís tu plan y pagás la primera cuota en línea.

<p align="center">
  <img src="assets/screenshots/pc/login.png" alt="Inicio de sesión" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/registro.png" alt="Registro con elección de plan" width="400">
</p>

## Para la recepción: el día de un vistazo

El panel del administrativo muestra los turnos reservados hoy, los clientes activos, cuántos están en lista de espera
y las próximas clases con su cupo. Desde ahí reserva para un cliente que llama por teléfono o registra un pago.

<p align="center">
  <img src="assets/screenshots/pc/admin-panel.png" alt="Panel del administrativo" width="820">
</p>

- **Clientes**: alta, modificación de datos y plan, y baja.
- **Actividades, turnos, planes y salas**: se arma la grilla semanal con profesor, sala y cupo de cada clase.
- **Cuotas y pagos**: registro del pago con comprobante; el estado del socio pasa de «en mora» a «al día».
- **Bonificaciones**: clases de regalo para los socios que no vinieron el mes anterior.
- **Reclamos y mantenimiento**: seguimiento de reclamos por estado e historial de tareas con su costo.
- **Auditoría**: cada cambio sobre reservas, asistencias, cupos y pagos queda registrado con quién, cuándo y qué
  cambió.

<p align="center">
  <img src="assets/screenshots/pc/admin-catalogo.png" alt="Actividades, turnos y planes" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/admin-pagos.png" alt="Registro de pago de cuota" width="400">
</p>

<p align="center">
  <img src="assets/screenshots/pc/admin-clientes.png" alt="Búsqueda de clientes" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/admin-bonificaciones.png" alt="Bonificaciones por inasistencia" width="400">
</p>

<p align="center">
  <img src="assets/screenshots/pc/admin-profesores.png" alt="Profesores" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/admin-asistencia.png" alt="Asistencia de las clases del día" width="400">
</p>

## Para el profesor: la nómina de cada clase

El profesor ve sus clases del día y la lista de inscriptos. La asistencia se marca durante la clase, desde la nómina
o con el lector de huella en la entrada, y nunca se cuenta dos veces.

<p align="center">
  <img src="assets/screenshots/pc/profesor-clases.png" alt="Mis clases" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/profesor-nomina.png" alt="Nómina de la clase" width="400">
</p>

## Para el dueño: números para decidir

Reportes por período de clientes activos por actividad, regularidad de asistencia e ingresos, gastos y pagos al
personal, con descarga en PDF y Excel.

<p align="center">
  <img src="assets/screenshots/pc/dueno-reporte-ingresos.png" alt="Ingresos, gastos y pagos al personal" width="820">
</p>

<p align="center">
  <img src="assets/screenshots/pc/dueno-reporte-activos.png" alt="Clientes activos y actividades" width="400">
  &nbsp;
  <img src="assets/screenshots/pc/dueno-reporte-regularidad.png" alt="Regularidad de asistencia" width="400">
</p>

## En el celular

Es una web instalable (PWA): se abre desde el navegador del celular y se agrega a la pantalla de inicio, sin
descargar nada de una tienda. Cada pantalla tiene su versión pensada para el dedo, con días en pestañas y barra de
navegación abajo.

<p align="center">
  <img src="assets/screenshots/movil/cliente-inicio.png" alt="Inicio en el celular" width="190">
  &nbsp;
  <img src="assets/screenshots/movil/cliente-actividades.png" alt="Actividades en el celular" width="190">
  &nbsp;
  <img src="assets/screenshots/movil/cliente-horarios.png" alt="Horarios en el celular" width="190">
  &nbsp;
  <img src="assets/screenshots/movil/cliente-confirmar.png" alt="Confirmar en el celular" width="190">
</p>

<p align="center">
  <img src="assets/screenshots/movil/cliente-reservado.png" alt="Turno reservado en el celular" width="190">
  &nbsp;
  <img src="assets/screenshots/movil/admin-panel.png" alt="Panel del administrativo en el celular" width="190">
  &nbsp;
  <img src="assets/screenshots/movil/profesor-nomina.png" alt="Nómina en el celular" width="190">
  &nbsp;
  <img src="assets/screenshots/movil/dueno-reporte-ingresos.png" alt="Reportes en el celular" width="190">
</p>

## Detrás de escena

- **Sin sobrecupos**: las reservas simultáneas sobre el último lugar se resuelven en la base de datos, y se probó con
  150 usuarios conectados a la vez.
- **Hora oficial**: todos los plazos (cancelación, lista de espera, recordatorios, mora) usan la hora de Argentina
  del servidor, nunca la del dispositivo.
- **Datos protegidos**: contraseñas con hash, datos sensibles cifrados, conexión segura y respaldo diario de la base.
- **Probado**: más de 400 pruebas automáticas, entre ellas las de aceptación de cada historia de usuario en
  navegador real, en tamaño de PC y de celular.
- **Pagos y lector de huella simulados**, detrás de una interfaz que permite conectar los reales sin tocar el resto.

> La demo corre en servidores gratuitos que se apagan cuando nadie los usa: el primer ingreso del día puede tardar
> hasta un minuto mientras «calienta motores». Después, todo va rápido.

## Hecha con

TypeScript · React · Vite · Tailwind · NestJS · PostgreSQL · Prisma · Playwright · Docker · Render

## Autor

Martín Sergio Sosa, Santino Percodani, Elias Rojas · [GitHub](https://github.com/martinsosa42)
