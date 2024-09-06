### ¿Como se manejan permisos en windows server?

En **Windows Server**, los permisos controlan el acceso a archivos, carpetas y recursos del sistema. Los principales mecanismos de gestión son:

1. **Permisos NTFS**: Controlan el acceso a archivos/carpetas en discos formateados con NTFS. Incluyen permisos básicos como Control total, Modificar, Leer y Escribir.

2. **Permisos compartidos**: Definen el acceso a carpetas compartidas en la red, combinándose con los permisos NTFS. Los principales son Leer, Cambiar y Control total.

3. **Políticas de seguridad local**: Gestionan permisos para aspectos del sistema mediante Directivas de seguridad local.

4. **Delegación de control**: Permite asignar permisos administrativos específicos en Active Directory.

5. **Group Policy (GPO)**: Aplica configuraciones y restricciones a usuarios/equipos dentro de un dominio.

6. **Auditoría de permisos**: Registra cambios y accesos a archivos para mejorar la seguridad.


### ¿Cual es la estructura de directorios de Windows server?

La **estructura de directorios de Windows Server** incluye:

1. **C:\Windows**: Carpeta del sistema operativo.
   - **System32**: Archivos del sistema.
   - **Temp**: Archivos temporales.
   - **Sysvol**: Archivos de Active Directory (en controladores de dominio).
   - **NTDS**: Base de datos de Active Directory.

2. **C:\Program Files**: Aplicaciones de 64 bits.
   - **Program Files (x86)**: Aplicaciones de 32 bits.

3. **C:\Users**: Perfiles de usuario.

4. **C:\inetpub**: Archivos de IIS (servidor web).
   - **wwwroot**: Archivos de sitios web.

5. **C:\ProgramData**: Datos compartidos entre aplicaciones.

6. **C:\PerfLogs**: Registros de rendimiento.

7. **C:\Windows\SoftwareDistribution**: Archivos de actualizaciones de Windows.

