#Subir Servidor

1. Abrir WinSCP
2. Protocolo: SFTP
3. IP: 
3. Puerto: 22
4. Usuario: soporte
5. Contraseña: soporte
6. Conectar

copiar ear en home/soporte

ssh soporte@svt-kq09b6y

borrar todo en deployments menos el .jar
borrar carpetas temp log data
copiar ear en deployments

tail -f /opto/rh/jboss    recepcion stan

sudo systemctl start max_recepcion_despacho_8380.service