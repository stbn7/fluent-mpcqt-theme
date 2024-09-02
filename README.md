
<div align="center">
	<h1>Tema Fluent Dark Mpc-Qt</h1>
	<p>
		<b> Tema Fluent Dark para el reproductor <a href="https://github.com/mpc-qt/mpc-qt">Media Player Classic Qute Theather</a>.
	</p>
	<br>
</div>


![img_2408291](https://github.com/user-attachments/assets/86e33b69-3c8a-4c03-88ca-1b8b0ea2568c)



### Instrucciones 
- Descargar <strong>mpc-qt v24.06</strong>
    
  ```
  wget https://github.com/mpc-qt/mpc-qt/archive/refs/tags/v24.06.zip
  ```

- Extraer el archivo `v24.06.zip`

  ```
  unzip v24.06.zip   
  ```
- Clonar este repositorio
  
  ```
  git clone https://github.com/stbn7/fluent-dark-mpcqt-theme.git
  ```
- Copiar todo el contenido de la carpeta `fluent-dark-mpcqt-theme` dentro de la carpeta `mpc-qt-24.06`

  ```
  cp -r fluent-dark-mpcqt-theme/* mpc-qt-24.06/   
  ```

- Finalmente, dentro de la carpera `mpc-qt-24.06` abre la terminal y ejecuta los siguientes comandos:

  ```
  qmake6
  make -j`nproc`
  sudo make install
  ```

Probado en KDE neon 6.0 con Qt Version 6.7.2
