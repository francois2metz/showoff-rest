!SLIDE

# 10 choses a ne PAS faire lorsque vous concevez une API REST. #

!SLIDE 

# 1. Ne pas penser la sécurité à la fin #

* Cookies
* gestion des permissions ..

!SLIDE

# 2. Utilisez les codes HTTP Standards #

* La classe des 2xx sont des codes de succès
* La classe des 3xx sont des codes redirection
* La classe des 4xx sont des codes d'erreur clients
* La classe des 5xx sont des codes d'erreurs serveurs

!SLIDE bullets incremental

Banisser:
* "404 Pas Permission"
* 500 lors d'une erreur de requêtes
* 200 lorsque tout a pété

!SLIDE

# 3. Versionnez correctement votre API #

Base d'uri toujours pareil.

Pas Bien:
* /dp/ws
* /dpv1/ws
* /dp/ws/v2
* /dp/wsp/v2

Bien:
* /dp/ws/1
* /dp/ws/2

!SLIDE

# 4. Tenez une documentation à jour #

L'ingénierie inverse c'est marrant deux minutes

!SLIDE

# 5. Utilisez des URI différentes pour chaque action #

!SLIDE

# 6. Testez #

* Client HTTP Standard
* Pour l'envoi de mail => fakemailserver
* Lancement de batch dans les tests

!SLIDE

# 7. Exposez votre numéro de version #

!SLIDE

# 8. Gardez une cohérence dans les paramètres #

* start-index qui des fois est startIndex
* max-results qui des fois est maxResults

!SLIDE

# 9. Le franglais c'est mal #

* /share/
* /documentsecurisee

!SLIDE

# 10. le xml de sortie DOIT etre valide  #

