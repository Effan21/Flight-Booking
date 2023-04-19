![icon_logo](https://i.ibb.co/RpXT993/icon-logo.png)

Application de réservation de vols d'avions faite avec le Framework Django

<img alt="flight" src="https://i.ibb.co/8dKZ6hH/scree.png">


### Fonctionnalités
1. Les utilisateurs peuvent créer leur compte utilisateur.
2. Les utilisateurs peuvent réserver des billets aller simple et aller-retour.
3. Les utilisateurs peuvent annuler leurs billets réservés.
4. Les utilisateurs peuvent voir leurs billets précédemment réservés (billets confirmés et annulés).
5. Les billets sont téléchargeables sous forme de document pdf.


### Fichiers et répertoires
   - `capstone` - répertoire du projet.
     - `utils.py` - Contient toutes les fonctions d'assistance Django utilisées dans views.py.
     - `urls.py` - Ce fichier gère toutes les URL du projet.
   - `flight` - répertoire principal de l'application.
     - `static` - contient tout le contenu statique.
         - `css` - Contient tous les fichiers CSS pour styliser les pages Web.
         - `js` - Contient tous les fichiers javascript utilisés dans l'application.
         - `img` - Contient tous les fichiers image utilisés dans l'application.
     - `templates/flight` Contient tous les modèles d'application.
         - `book.html` - Modèle pour afficher le vol sélectionné et lire les données des voyageurs.
         - `bookings.html` - Modèle pour afficher les réservations effectuées par un utilisateur.
         - `index.html` - Modèle de page d'accueil.
         - `layout.html` - Modèle de base pour toutes les pages sauf la page de connexion et d'inscription.
         - `layout2.html` - Modèle de base pour la page de connexion et d'inscription.
         - `login.html` - Page utilisateur de connexion.
         - `payment_process.html` - Page après l'achèvement du paiement.
         - `payment.html` - Page de paiement.
         - `register.html` - Page d'enregistrement de l'utilisateur.
         - `search.html` - Page de résultats de la recherche de vols.
         - `ticket.html` - Modèle pour l'impression du ticket (pdf).
     - `admin.py` - Contient quelques modèles pour l'accès à l'administrateur Django.
     - `models.py` - Tous les modèles utilisés dans l'application sont créés ici.
     - `urls.py` - Ce fichier gère toutes les URL de l'application Web.
     - `views.py` - Ce fichier contient toutes les vues de l'application.
     - `constant.py` - Ce fichier contient le montant des frais facturés à l'utilisateur pour la réservation de billets d'avion.
   - `requirements.txt` - Ce fichier contient tous les packages python qui doivent être installés pour exécuter cette application Web.
   - `manage.py` - Ce fichier est essentiellement utilisé comme utilitaire de ligne de commande et pour déployer, déboguer ou exécuter notre application Web.


### Installation

- Activez l'environnement virtuel en exécutant `venv\Scripts\activate`
- Installez les dépendances du projet en exécutant `py -m pip install -r requirements.txt`.
- Créez un superutilisateur avec `py manage.py createsuperuser`. Cette étape est facultative.
- Exécutez la commande `py manage.py runserver` pour exécuter le serveur Web.
- Ouvrez le navigateur Web et accédez à l'URL `127.0.0.1:8000` pour commencer à utiliser l'application Web.

