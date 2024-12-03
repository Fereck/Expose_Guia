# Expose_Guia
pwn a Linux machine.


Hacemos un escaneo de puertos para analizar el equipo objetivo en este caso es "10.10.173.250"

	Nmap 10.10.173.250 -sC -sV -Pn



![image](https://github.com/user-attachments/assets/502a5187-215b-46fe-b470-b8819f45e566)

## Usamos los parametros `-sC` `-sV` `-Pn`:

### Significados:

`-sC`: Usa scripts basicos de deteccion.
`-sV`: Detecta versiones de los servicios.
`-Pn`: Desactiva la deteccion por Hosts.

![image](https://github.com/user-attachments/assets/d69486c9-a40d-4501-8c68-962e500ebf2a)

Vemos que se puede hacer Login de manera anonima.

	`ftp 10.10.173.250`	

`anonymous` 

En password damos `enter` y listo. 	


Revisamos si tiene archivos con un `ls -a`
