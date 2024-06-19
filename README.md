Ejecución del Script:
Para ejecutar este script desde cmd:

Guardar el script: Asegúrate de que el script esté guardado en el escritorio con el nombre monitor_server.ps1.

Abrir cmd como Administrador:

Presiona Windows + X y selecciona "Símbolo del sistema (Admin)" o "Windows Terminal (Admin)" si estás en una versión más reciente de Windows.
Cambiar la política de ejecución (si es necesario):

Puedes cambiar la política de ejecución temporalmente usando el siguiente comando en cmd:

>powershell -Command "Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process"

Navegar al escritorio:

Usa cd para cambiar al directorio del escritorio
Esto es opcional depende mucho de donde guardaste tu SCRIPT
>cd %USERPROFILE%\Desktop


Ejecutar el script:

Usa el siguiente comando para ejecutar el script PowerShell desde cmd:
>powershell -File watcherServer.ps1
