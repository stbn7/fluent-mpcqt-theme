
<div align="center">
	<h1>Tema Fluent Mpc-Qt</h1>
	<p>
		<b> Tema Fluent Dark para el reproductor <a href="https://github.com/mpc-qt/mpc-qt">Media Player Classic Qute Theather</a>.
	</p>
	<br>
</div>


![img_2408291](https://github.com/user-attachments/assets/86e33b69-3c8a-4c03-88ca-1b8b0ea2568c)



### Instrucciones 
- Clonar el repositorio <a href="https://github.com/mpc-qt/mpc-qt">Mpc-qt</a> usando el siguiente comando: 
    
  ```
  git clone https://github.com/mpc-qt/mpc-qt.git
  ```
- Clonar este repositorio:
  
  ```
  git clone https://github.com/stbn7/fluent-dark-mpcqt-theme.git
  ```
- Copiar todo el contenido de la carpeta `fluent-dark-mpcqt-theme` dentro de la carpeta del repositorio <strong>mpc-qt</strong>

- Finalmente, dentro de la carpera <strong>mpc-qt</strong> abre la terminal y ejecuta los siguientes comandos:

  ```
  qmake6
  make -j`nproc`
  sudo make install
  ```

Probado en KDE neon 6.0 con Qt Version 6.7.2
