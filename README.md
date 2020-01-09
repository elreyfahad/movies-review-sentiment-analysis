# Analyzing Movie Reviews Sentiment :
L'objectif principal de ce chapitre est de prédire le sentiment pour un certain nombre de critiques de films obtenues à partir de l'Internet Movie Database (IMDb). Cet ensemble de données contient 50 000 critiques de films qui ont été pré-étiquetées avec des étiquettes de classe de sentiments «positives» et «négatives» en fonction du contenu de la critique. En plus de cela, il y a des critiques de films supplémentaires qui ne sont pas étiquetées. L'ensemble de données peut être obtenu auprès de http://ai.stanford. edu/~amaas/data/sentiment/, avec l'aimable autorisation de l'Université de Stanford et Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng et Christopher Potts. Cet ensemble de données a également été utilisé dans leur célèbre article, Learning Word Vectors for Sentiment Analysis résultats de la 49e réunion annuelle de l'Association for Computational Linguistics (ACL 2011). Ils ont des ensembles de données sous forme de texte brut ainsi que des formats de sacs de mots déjà traités. Nous n'utiliserons que les critiques de films étiquetées brutes pour nos analyses dans ce chapitre. Par conséquent, notre tâche sera de prédire le sentiment de 15 000 critiques de films étiquetés et d'utiliser les 35 000 critiques restantes pour former nos modèles supervisés. Nous prédirons toujours les sentiments pour seulement 15 000 avis en cas de modèles non supervisés afin de maintenir la cohérence et de faciliter la
