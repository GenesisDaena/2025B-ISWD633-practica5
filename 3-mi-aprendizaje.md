# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

Después de completar la práctica aprendí a crear archivos docker-compose.yaml bien estructurados para levantar aplicaciones multi-servicio como WordPress-MySQL y SonarQube-PostgreSQL. Comprendí más de las variables de entorno y cómo se usan para conectar múltiples servicios dockerizados.
Entendí la importancia de definir platform: linux/amd64 para evitar errores de compatibilidad entre mi sistema operativo Windows y las imágenes que, aunque corren sobre una máquina virtual Linux, utilizan imágenes preparadas para otras arquitecturas. Aprendí a gestionar y solucionar problemas con imágenes corruptas de Docker, detectar errores de formato como exec format error y limpiar completamente imágenes, volúmenes y contenedores para realizar instalaciones limpias. Entendí mejor el uso y ajustes del parámetro healthcheck para garantizar que los servicios estén operativos antes de que otros dependan de ellos.

Solución a problemas presentados:

Durante la práctica enfrenté varios problemas, principalmente relacionados con la descarga de imágenes incompatibles o corruptas, especialmente MySQL, errores de arquitectura y manejo de espacio en disco. Para solucionarlos aprendí a forzar la descarga correcta de imágenes con el parámetro --platform linux/amd64 y a limpiar caché de imágenes defectuosas y reconfiguré Docker Desktop para mover todos los volúmenes e imágenes al disco D y evitar saturar espacio en el disco C.
