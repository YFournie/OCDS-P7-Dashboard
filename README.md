# Implémenter un modèle de scoring

# 1. Pour voir tout le travail sur ce projet
Bonjour ! Ce repository a été créé dans le cadre d'un projet de formation de Data Scientist.
Il est indissociable des deux autres repositories que vous trouverez à ces adresses :
- Pour l'entrainement du modèle : https://github.com/YFournie/OC-DS-P7
- Pour l'API (avec Flask) : https://github.com/YFournie/OCDS-P7-API

# 2. Présentation des enjeux
Les enjeux du projet en lui-même sont présentés dans le repository sur l'entrainement du modèle (lien ci-dessus)

Dans cette partie, avec Streamlit, je déploie en ligne un Dashboard à destination du banquier qui, lui, n'a pas les connaissances nécessaires à la compréhension du modèle.
Lien de l'API : https://yfourniep7app-ff49685dca43.herokuapp.com
Lien du Dashboard : https://yfourniedashboard.streamlit.app/
(Comme cela coûte de l'argent de maintenir l'API en ligne, il est possible qu'au moment où vous testez ces liens, vous rencontriez une erreur. Si vous souhaitez visualiser ceci, veuillez me contacter)

L'objectif est d'obtenir un outil "clé en main" pour le banquier.
- Il peut lire le score du client et si le prêt est accepté ou non
- Il peut ensuite regarder certaines caractéristiques du client selon son choix
- Il peut demander au modèle quelles sont les caractéristiques qui l'ont amené à prendre sa décision
- Il peut faire comparer les caractéristiques les plus importantes à d'autres clients similaires

# 3. Faire tourner ce projet
Pour ce qui est des packages nécessaires, ils sont dans le requirements.txt
La seule chose qu'il vous reste à faire, c'est de modifier le "path" au début de chaque notebook par celui qui vous conviendra, en fonction de votre organisation de fichiers.

# 4. Si vous êtes aussi étudiant chez OC...

... Et que vous tombez sur mon travail, je ne vous encourage pas à le copier, en revanche, vous pouvez vous en inspirer.
Comme je le disais plus tôt, si vous souhaitez visualiser mon Dashboard par exemple, vous pouvez me contacter pour que je réactive l'API.
