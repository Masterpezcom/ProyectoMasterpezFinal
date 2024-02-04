Este proyecto tuvo su origen en mi primer repositorio llamado FacturacionMasterpez (https://github.com/Masterpezcom/FacturacionMasterPez). Inicialmente, se desarrolló utilizando Angular 16 con TypeScript y tenía una base de datos alojada en Firestore Database de Google Firebase (https://facturacion-masterpez.web.app/sesion), donde ya estaba implementado y operativo. Sin embargo, opté por realizar un cambio significativo migrando a C# y SQL Server, empleando el marco de trabajo Entity Framework Core en una aplicación .NET. La decisión se basó en la gestión más eficiente de la base de datos, dada su pequeña escala y la conveniencia que ofrecía esta tecnología.

El frontend del proyecto está íntegramente escrito en TypeScript, HTML, JS y CSS, haciendo uso del framework Angular (CLI y Material). Para mejorar la experiencia del usuario, se implementó el componente de notificación emergente MatSnackBar de la biblioteca Angular Material. Adicionalmente, se incorporó código de Bootstrap para optimizar la presentación en la interfaz de inicio de sesión.

Cabe señalar que, hasta la fecha, el proyecto no ha sido desplegado en la nube. Intenté llevar a cabo el despliegue en Google Cloud, pero se me solicitó información de pago, ya que había superado el periodo de prueba gratuito ofrecido por el proveedor.
