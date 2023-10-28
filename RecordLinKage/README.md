# RecordLinKage

<div align="center">

  
  <a href="https://github.com/1treu1/Deduplicacion-de-Datos/tree/main/RecordLinKage" target="_blank">
    <img width="1024", src="https://recordlinkage.readthedocs.io/en/latest/_images/indexing_basic.png" width="500" height="500"></a>


<br>
  <a href="https://colab.research.google.com/drive/1t6wKMkjDRyG1NvLqMpvxuZdwLfO3nUua?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
  <a href="https://github.com/1treu1/Deduplicacion-de-Datos/tree/main/RecordLinKage"><img src="https://img.shields.io/badge/github-Open In Github-brightgreen.svg" alt="Open In Github"></a>
</br>

</div>

Esta libreria permite cencontrar registros duplicados usando varios algoritmos de similitud semantica. Estos son algunos que maneja la libreria:

* Jaro–Winkler distance: https://en.wikipedia.org/wiki/Jaro%E2%80%93Winkler_distance 
* Jaro Similarity: https://rosettacode.org/wiki/Jaro_similarity 
* Levenstein Distance: https://en.wikipedia.org/wiki/Levenshtein_distance

Problema:
- En Mercado libre tienen una base de datos inmensa en su ERP de SIESA. Entre los datos maestros esta la informacion de los clientes. Debido a malas practicas, hay muchos registros dupicados, que hacen que la calidad de los datos no sea la esperada. 
Se necesita hallar todos los duplicados de la base de datos y dejar un registro unico de los clientes.

Solucion:
- Usar RecordLinkage para entrenar un modelo NLP con el fin de agrupar los registros duplicados en la base de datos
