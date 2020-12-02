
![TheliaKingAvis](https://github.com/kevinseebach/TheliaKingAvis/blob/master/theliaking.jpg?raw=true)
Synchronisez votre boutique ecommerce sous Thelia 2 vers la plateforme de récolte d'avis client KingAvis. Récoltez l'avis de vos clients sur leurs commandes et boostez vos ventes.


## Installation
-   Copiez le module dans le repertoire  `<thelia_root>/local/modules/`   de votre boutique Thelia
- Assurez vous que le dossier nouvellement ajouté s'appelle bien KingAvis.
-   Activez le module dans l'administration Thelia.
-   Configurez le module.

## Configuration
1.   Connectez vous à votre compte KingAvis et récupérer vos informations de connection disponibles dans la rubrique Mon Compte
![Trouvez vos identifiants](https://github.com/kevinseebach/TheliaKingAvis/blob/master/integration-code-manuel-2.jpg?raw=true)

2.   Configuez votre module dans Thelia. Dans votre admin aller à la page `Modules` puis configurez le module KingAvis
3. Renseignez les informatiosn récupérer en 1.
![TheliaKingAvis](https://raw.githubusercontent.com/kevinseebach/TheliaKingAvis/master/configThelia.jpg?raw=true)
4. Choisissez le statut de commande qui déclenchera la synchronisation (Payée ou Envoyée sont recommandés)
5.  Choisissez d'afficher ou non le widget sur votre site. Sa position peut être définie dans votre compte KingAvis dans la rubrique `Mon Compte -> Mon Widget`
6. Validez et récoltez vos avis client


## Fonctionnement
Lorsque la commande passe au status choisit, elle est automatiquement envoyer sur la plateforme. Le mail de demande d'avis sera alors automatiquement envoyer selon votre configuration KingAvis (par défaut 10 jours après mais modifiable dans la section Demande Avis Automatique de votre compte).


## Voir également

- [KingAvis](https://king-avis.com/fr/) - Plateforme d'avis client francophone, simple et gratuite
- [Thelia 2 ](https://thelia.net/?lang=fr_FR) - [Thelia 2 sur Github](https://github.com/thelia/thelia) - Solution Ecommerce française sous PHP
