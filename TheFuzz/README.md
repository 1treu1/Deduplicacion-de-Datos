  # TheFuzz

<div align="center">


  <a href="https://github.com/1treu1/Deduplicacion-de-Datos/tree/main/TheFuzz" target="_blank">
    <img width="1024", src="https://m.media-amazon.com/images/S/pv-target-images/39981144ca9d92fcfa857223ea889663d35999d5fae146d42f658cf7c49f025a.jpg" width="800" height="400"></a>


<br>
  <a href="https://colab.research.google.com/drive/1LMZnbyKUBBGIzB7fPmd2dhI6KNpJ_MHO?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
  <a href="https://github.com/1treu1/Deduplicacion-de-Datos/tree/main/TheFuzz"><img src="https://img.shields.io/badge/github-Open In Github-brightgreen.svg" alt="Open In Github"></a>
</br>
Esta libreria permite encontrar registros duplicados usando la distancia de Levenstein. 
</div>


* Levenstein Distance: https://en.wikipedia.org/wiki/Levenshtein_distance

Problema:
- En Mercado libre tienen una base de datos inmensa en su ERP de SALESFORCES. Entre los datos maestros esta la informacion de los clientes. Debido a malas practicas, hay muchos registros dupicados, que hacen que la calidad de los datos no sea la esperada. 
Se necesita hallar todos los duplicados de la base de datos y dejar un registro unico de los clientes.

Solucion:
- Usar TheFuzz para entrenar un modelo NLP con el fin de agrupar los registros duplicados en la base de datos
