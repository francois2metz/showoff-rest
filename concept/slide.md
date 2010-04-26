!SLIDE

# 10 choses a ne PAS faire lorsque vous concevez une API REST. #

!SLIDE bullets incremental

# 1. Penser la sécurité à la fin #

* Cookies
* Gestion des permissions ..

!SLIDE bullets incremental

# 2. Utiliser les codes HTTP Standards sans rapport avec ce qui c'est passé #

* "404 Pas Permission"
* 500 lors d'une erreur de requêtes
* 200 lorsque tout a pété

!SLIDE bullets incremental

* La classe des 2xx sont des codes de succès
* La classe des 3xx sont des codes redirection
* La classe des 4xx sont des codes d'erreur clients
* La classe des 5xx sont des codes d'erreurs serveurs

!SLIDE bullets incremental

# 3. Le versionnage aléatoire #

Pas bien

* /dp/ws
* /dpv1/ws
* /dp/ws/v2
* /dp/wsp/v2

!SLIDE bullets incremental

Bien:

* /dp/ws/1
* /dp/ws/2

!SLIDE

# 4. La documentation pas à jour #

## L'ingénierie inverse c'est marrant deux minutes ##

!SLIDE bullets incremental

# 5. Utiliser les mêmes URI pour des actions différentes #

## PUT /user/$userId ##

* Modification de l'utilisateur
* Réinitialisation des identifiants

!SLIDE bullets incremental

# 6. Chuck Norris ne teste pas, moi non plus #

* Client HTTP Standard
* Pour l'envoi de mail => fakemailserver
* Lancement de batch dans les tests

!SLIDE

# 7. Le PUT remplace partiellement une ressource #

## Le PUT remplace totalement une ressource (en théorie). ##

!SLIDE bullets incremental

# 8. Des paramètres non uniformes entre services #

* start-index qui des fois est startIndex
* max-results qui des fois est maxResults

!SLIDE bullets incremental

# 9. Le franglais c'est amusant #

* /share/
* /documentsecurisee

!SLIDE

# 10. le xml de sortie DOIT etre valide  #

## C'est déjà une API pas vraiment REST, il ne faudrait pas qu'elle soit XML aléatoirement ##


