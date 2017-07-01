# Loggeur IFTA

## Utilisation

Pour logger ton milage IFTA automatiquement.

### Bugs

## Bug cordova_plugins.js

Bug bizarre : Tu vas avoir une erreur cordova_plugins.js bloqué à cause MIME je sais pas quoi. Le fix c'est d'installer le plugin cordova-background-geolocation-lt avec 

    phonegap plugin add cordova-background-geolocation-lt
    
et comme par magie, le navigateur va cesser de chiâler. Même si le plugin que tu viens d'installer ne fonctionne pas sur les browsers et l'app non native...

Cela dit, pour que l'app fonctionne autonomement, il faudra utiliser ce plugin. So il n'y a rien de perdu de l'inclur tout de suite dans le projet.

