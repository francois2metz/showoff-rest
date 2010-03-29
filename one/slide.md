!SLIDE
# 10 choses a ne PAS faire lorsque vous concevez une API REST. #

!SLIDE 

# Ne pas penser la sécurité à la fin #

* Cookies
* gestion des permissions ..

!SLIDE

# Utilisez les codes HTTP Standards #

* La classe des 2xx sont des codes de succés
* La classe des 3xx sont des codes redirection
* La classe des 4xx sont des codes d'erreur clients
* La classe des 5xx sont des codes d'erreurs serveurs

!SLIDE bullets incremental

Banisser:
* "404 Pas Permission"
* 500 lors d'une erreur de requêtes
* 200 lorsque tout a pété

!SLIDE

# Versionnez correctement votre API #

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

# Tenez une documentation à jour #

!SLIDE

# Utilisez des URI différences pour chaque action #

!SLIDE

# Testez #

* Client HTTP Standard
* Pour l'envoi de mail => fakemailserver
* Lancement de batch dans les tests

!SLIDE

# Exposez votre numéro de version #







