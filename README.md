# Application Météo Flutter

Une application Flutter simple qui affiche un quiz et les prévisions météorologiques pour une ville donnée en utilisant l'API OpenWeatherMap.

## Table des matières
* [Fonctionnalités](#fonctionnalités)
* [Captures d'écran](#captures-décran)
* [Prérequis](#prérequis)
* [Installation](#installation)
    * [Configuration de la Clé API](#configuration-de-la-clé-api)
* [Auteur](#auteur)

## Fonctionnalités

*   Quiz : Application simple avec des questions et réponses.
*   Météo : Recherche de prévisions météorologiques par nom de ville.
*   Affichage des prévisions pour plusieurs jours/heures (selon l'API).
*   Gestion distincte des clés API pour les builds Web et mobiles/desktop.

## Captures d'écran

### Écran Quiz (version Mobile)

<p align="center">
  <em>Question1 et choix de réponses</em><br/>
  <img src="assets/images/Capture_quiz_1.png" alt="Question1 et choix de réponses" width="350"/>
</p>

<p align="center">
  <em>Question2 et choix de réponses</em><br/>
  <img src="assets/images/Capture_quiz_2.png" alt="Question2 et choix de réponses" width="350"/>
</p>

<p align="center">
  <em>Score et recommencer</em><br/>
  <img src="assets/images/Capture_quiz_score_ok.png" alt="Score et recommencer" width="350"/>
</p>

<p align="center">
  <em>Réponse incorrecte et score</em><br/>
  <img src="assets/images/Capture_quiz_score_ko_1.png" alt="Réponse incorrecte et score" width="350"/>
</p>

<p align="center">
  <em>Réponse incorrecte et score</em><br/>
  <img src="assets/images/Capture_quiz_score_ko_2.png" alt="Réponse incorrecte et score" width="350"/>
</p>

### Écran Quiz (version Web)

![Écran Quiz](assets/images/Capture_quiz_version_web.png)


### Écran prévisions météo (version Mobile)

<p align="center">
  <em>Météo d'une ville donnée</em><br/>
  <img src="assets/images/Capture_weather.png" alt="Météo d'une ville donnée" width="350"/>
</p>

### Écran prévisions météo (version Web)

![Écran Météo](assets/images/Capture_weather_version_web.png)


## Prérequis

*   Flutter SDK (version [VOTRE_VERSION_FLUTTER_SI_SPECIFIQUE, ex: 3.x.x] ou supérieure)
*   Dart SDK (inclus avec Flutter)
*   Un IDE comme Android Studio ou Visual Studio Code avec les plugins Flutter/Dart.
*   Une clé API valide de [OpenWeatherMap](https://openweathermap.org/api).

## Installation

1.  **Clonez le dépôt :**
2.  **Installez les dépendances Flutter :**
    Assurez-vous que vous avez les dépendances Flutter installées (http, intl, weather_icons, flutter_dotenv)

    ![Écran Dependances](assets/images/Capture_dependances.png)

3.  **Configuration de la Clé API :**

    Cette application nécessite une clé API OpenWeatherMap pour fonctionner.

    *   **Pour les plateformes mobiles/desktop (Android, iOS, Desktop) :**
        1.  Créez un dossier `assets` à la racine de votre projet s'il n'existe pas.
        2.  À l'intérieur du dossier `assets`, créez un fichier nommé `.env`.
        3.  Ajoutez votre clé API dans ce fichier (OPENWEATHER_API_KEY=XXXXX) comme suit :    
        4.  **Exécutez l'application :**
            *   Sélectionnez un appareil (émulateur, appareil physique ou 'Chrome'/'Web Server' pour le web).
            *   Lancez l'application depuis votre IDE ou via la commande :
                (N'oubliez pas l'option `--dart-define` si vous exécutez pour le web comme indiqué ci-dessus).
                ![conf_web](assets/images/Capture_conf_version_web.png)
                

## Auteur

*   **[elghariaoui]**
    
