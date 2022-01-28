Proyecto Final Web Scraper con Python

Instrucciones :

Primero: se deben importar las librerías pandas as pd, pandasql as ps, time, numpy as np (sino se tienen instaladas habrá que instalarlas).

Segundo: se debe instalar selenium en nuestro anaconda (puede implementar el método .pip para su instalación) ya que hallamos instalado
selenium debemos descargar nuestro webdriver el cual lo descargaremos de la siguiente liga: "https://chromedriver.chromium.org/downloads" 
debemos fijarnos que versión de chrome tenemos en nuestro equipo para así instalar la versión correspondiente.

Tercero: importamos nuestro webdriver de selenium, también importamos matplotlib.pyplot as plt.

Cuarto: En el apartado "path = " necesitará escribir la dirección donde tenga instalado su webdriver, de la siguiente manera:
r"dirección de su webdriver\chromedriver.exe" esto lo debera hacer en cada scraper de cada una de las paginas web, este punto es 
muy importante ya que sino se coloca correctamente la ruta del webdriver no se podra ejecutar correctamente todo el programa.
