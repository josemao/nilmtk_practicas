Notas: 
- Para solucionar los errores en los notebooks de desagregación instalar la version 0.16.2 de pandas: 


	conda install pandas==0.16.2

- En la máquina Linux, si se quiere tener una carpeta compartida con la máquina: 
	- En rc.local: "mount -t vboxsf -o rw,uid=1000,gid=1000 data /home/nilm/Escritorio/data/"
	- Seguir estos pasos: 
		https://forums.virtualbox.org/viewtopic.php?t=15868#p66406
		http://askubuntu.com/questions/481559/how-to-automatically-mount-a-folder-and-change-ownership-from-root-in-virtualbox

