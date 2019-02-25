Copiar y obtener el link compartido
==================================

Con rclone help tenemos todos los comandos, pero para realizar una copia de una archivo local hacia el Google drive que ya configuramos es::

	$ rclone copy CONSIS.png gdrive:

Con el siguiente comando listamos todos los archivos que estan el la raiz de Google Drive::

	$ rclone ls gdrive:
	398286458 CONSIS.G-7130.ear
	    11689 CONSIS.png
	448988295 HF-RURAL-20181128-G-1037.tar.gz
	412456224 RE-CRECER-20181116-G-7490.tar.gz
	   580667 README.txt
	     2719 hl2-hn.tar.gz

Con el siguiente comando obtenemos el link para compartir::

	$ rclone link gdrive:CONSIS.png
	https://drive.google.com/open?id=1C0-kUV7kD6Mt2cRxsoQD8eA10KUNz5AM

