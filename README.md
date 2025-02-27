# SmartTweet

**Twitter** est un réseau social créé en 2006 qui compte plus de **300 millions d’utilisateurs** actifs par mois. C’est un des réseaux sociaux les plus utilisés dans le monde à l’heure actuelle. Il permet à un utilisateur d’envoyer de brefs messages, appelés tweets (280 caractères maximum) auxquels il est possible d’ajouter des images ou des vidéos notamment.

L’objectif principal de ce projet est de **mettre en oeuvre des algorithmes d’apprentissage par réseaux de neurones profonds** pour effectuer une **classification multimodale** des tweets, cette classification se basant à la fois sur le texte et sur les éventuelles images contenues dans un tweet.
Un objectif complémentaire de ce projet est d’**élaborer un modèle génératif** qui serait capable d’alimenter un bot Twitter thématique respectant le style et la cohérence d’une thématique donnée.

Nous nous sommes majoritairement consacrées à l’objectif central de ce projet. Nous avons, pour cela, **évalué la qualité des ressources** mises à notre disposition pour construire notre base de données. Nous avons ensuite construit un réseau permettant la classification des tweets en se basant uniquement sur le texte, puis un réseau permettant la classification des tweets en se basant uniquement sur les images. Nous avons finalement mis en oeuvre deux réseaux multimodales alliant à la fois le texte et l’image : un modèle **early fusion** et un modèle **late fusion**.
