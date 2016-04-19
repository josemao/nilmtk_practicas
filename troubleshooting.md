Notas: 
- Para solucionar los errores en los notebooks de desagregación, copiar de nuevo redd.h5
- Compartir carpeta: 
	- Seguir estos pasos: 
		https://forums.virtualbox.org/viewtopic.php?t=15868#p66406
		http://askubuntu.com/questions/481559/how-to-automatically-mount-a-folder-and-change-ownership-from-root-in-virtualbox
	- En rc.local: "mount -t vboxsf -o rw,uid=1000,gid=1000 data /home/nilm/Escritorio/data/""