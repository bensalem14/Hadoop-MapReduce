pour la seconde partie, nous avons utilisé hadoop map reduce pour 
compter les occurrences de mots dans un très gros fichier. 
cette partie a été implémentée dans google collab

-dans le fichier hadoop.ipynb nous avons installé les logiciels nécessaires (java , hadoop) , le code pour le mapping est fourni dans mapper.py et  le code pour la réduction est fourni dans reduce.py
-Que nous utilisions java ou python, le mappeur et le réducteur doivent toujours être séparés du code principal (en java, nous les encapsulant dans une classe et utilisons la commande job.setMapperClass/job.setReducerClass).
-Ces deux fichiers seront exécutés sur tous les fichiers texte de 20news-18828. qui est extrêmement volumineux (32MO sous la forme tar)
-Les résultats seront stockés dans le fichier PART-00000 généré automatiquement.(plus 15300 mots)
-Le temps d'éxcution a été 40.604s sur 2 core 12threads
-20news-18828.tar.gz  contient les grand fichier dans lequelles le traitement va etre executer 


