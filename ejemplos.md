# Ejemplos Wget  

## 1. Descargar archivos individuales  

![Ejemplo1](https://github.com/anasalasro/Wget/blob/main/wget/wget.png)

## 2. Descargamos varios archivos juntos desde un fichero de texto
![Ejemplo2](https://github.com/anasalasro/Wget/blob/main/wget/ejemplo2.png)
![Ejemplo1](https://github.com/anasalasro/Wget/blob/main/wget/viejemplos.png)
![Ejemplo1](https://github.com/anasalasro/Wget/blob/main/wget/ejemplo3.png)

## 3. Utilizar wget para descargar archivos con un nombre diferente
      wget -O wordpress-install.zip 
      https://wordpress.org/latest.zip
      
## 4. Utilizar wget para descargar archivos en un directorio concreto
      wget -P documents/archives/
      https://wordpress.org/latest.zip
      
## 5. Utilizar wget para descargar archivos en segundo plano
      wget -b http://example.com/beefy-file.tar.gz
      
## 6. Utilizar wget para descargar archivos con la descarga interrumpida
      wget -c https://example/very-big-file.zip
      
## 7. Utilizar wget para descargar sitios webs completos
      wget --mirror --convert-links --page-requisites --no-parent -P documents/websites/ https://some-website.com
