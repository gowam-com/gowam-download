Netherlands versie onder

# FR

## Installer Gowam Admin sur Windows

1. **Télécharger Gowam Admin**
    - Téléchargez la [dernière version de Gowam Admin](https://github.com/gowam-com/gowam-download/raw/refs/heads/main/gowam-admin-windows.zip).

2. **Décompresser l'archive**
    - Extrayez le contenu du fichier téléchargé dans le dossier de votre choix.
    
3. **Lancer l'application**
    - Double-cliquez sur le fichier `GowamAdmin.exe` pour démarrer l'application d'administration.

4. **Se connecter à Gowam Admin**
    - Entrez votre **nom d'utilisateur** et **mot de passe** qui vous ont été envoyés par mail.
    - Cliquez sur **Sign in** pour accéder à l'application d'administration.

5. **Ajouter un nouvelle entreprise (votre client)**
    - Cliquez sur l'icône dans le coin supérieur gauche pour ouvrir le menu principal.
    - Sélectionnez le menu **Add company, user and database** pour ajouter une entreprise, un utilisateur et une base de données.
    - Pour la nouvelle entreprise, renseignez :
        - **Code** de l'entreprise du client
        - **Nom** de l'entreprise du client
        - **Numéro de TVA** du client (important pour PEPPOL)
    - Pour le nouvel utilisateur, renseignez :
        - **Adresse mail** du client
        - **Nom d'utilisateur** en y remplissant également l'adresse mail du client (afin d'assurer l'unicité du l'utilsateur sur notre API)
        - **Mot de passe**
    - Pour la base de données, sélectionnez le type **Peppol only** si vous installez Gowam PEPPOL-DBF.
    - Cliquez sur le bouton **Save** pour terminer l'ajout de l'entreprise, de l'utilisateur et de la base de données.

6. **Envoyer les identifiants à l'utilisateur**
    - Cliquez sur le bouton **Users** de la nouvelle entreprise créée.
    - Sélectionnez l'utilisateur que vous venez d'ajouter.
    - Cliquez sur le bouton **Email the credentials** pour envoyer par email les identifiants à cet utilisateur.

## Installer Gowam PEPPOL-DBF ou Local-Only sur Windows

1. **Télécharger Gowam**
    - Téléchargez la [dernière version de Gowam](https://github.com/gowam-com/gowam-download/raw/refs/heads/main/gowam-windows.zip).

2. **Décompresser l'archive**
    - **IMPORTANT**: Dans le répertoire de la workstation (obligatoire pour la version PEPPOL-DBF), créez un nouveau dossier nommé `gowam`.
    Choisissez le dossier de votre choix pour la version Local-Only.
    - Extrayez le contenu du fichier téléchargé dans ce nouveau dossier `gowam`.
    
3. **Lancer l'application**
    - Dans le dossier `gowam`, double-cliquez sur le fichier `gowam.exe` pour démarrer l'application.

4. **Initialiser Gowam**
    - Entrez le **nom d'utilisateur pour l'API** et le **mot de passe** créés dans Gowmam Admin, ainsi qu'une description de l'appareil où Gowam est installé.
    - Cliquez sur **Se connecter au cloud** pour initialiser Gowam et passez à l'écran de connexion.

4. **Ouvrir un dossier**
    - Entrez le **nom d'utilisateur** et l'éventuel **mot de passe**, et sélectionnez le dossier à ouvrir.
    - Cliquez sur **Sign in** pour accéder au dossier sélectionné.

# NL

## Gowam Admin installeren op Windows

1. **Gowam Admin downloaden**
    - Download de [laatste versie van Gowam Admin](https://github.com/gowam-com/gowam-download/raw/refs/heads/main/gowam-admin-windows.zip).

2. **Het archief uitpakken**
    - Pak de inhoud van het gedownloade bestand uit in een map naar keuze.

3. **De applicatie starten**
    - Dubbelklik op het bestand `GowamAdmin.exe` om de beheertoepassing te starten.

4. **Inloggen op Gowam Admin**
    - Voer uw **gebruikersnaam** en **wachtwoord** in die u per e-mail heeft ontvangen.
    - Klik op **Sign in** om toegang te krijgen tot de beheertoepassing.

5. **Een nieuw bedrijf (uw klant) toevoegen**
    - Klik op het pictogram linksboven om het hoofdmenu te openen.
    - Selecteer het menu **Add company, user and database** om een bedrijf, gebruiker en database toe te voegen.
    - Vul voor het nieuwe bedrijf in:
        - **Code** van het klantbedrijf
        - **Naam** van het klantbedrijf
        - **BTW-nummer** van de klant (belangrijk voor PEPPOL)
    - Vul voor de nieuwe gebruiker in:
        - **E-mailadres** van de klant
        - **Gebruikersnaam** en vul ook het e-mailadres van de klant in (om uniciteit van de gebruiker op onze API te garanderen)
        - **Wachtwoord**
    - Selecteer voor de database het type **Peppol only** als u Gowam PEPPOL-DBF installeert.
    - Klik op de knop **Save** om het bedrijf, de gebruiker en de database toe te voegen.

6. **De inloggegevens naar de gebruiker sturen**
    - Klik op de knop **Users** van het nieuw aangemaakte bedrijf.
    - Selecteer de gebruiker die u zojuist heeft toegevoegd.
    - Klik op de knop **Email the credentials** om de inloggegevens per e-mail naar deze gebruiker te sturen.

## Gowam PEPPOL-DBF of Local-Only installeren op Windows

1. **Gowam downloaden**
    - Download de [laatste versie van Gowam](https://github.com/gowam-com/gowam-download/raw/refs/heads/main/gowam-windows.zip).

2. **Het archief uitpakken**
    - **BELANGRIJK**: Maak in de workstation-directory (verplicht voor de PEPPOL-DBF-versie) een nieuwe map genaamd `gowam`.
    Kies een map naar keuze voor de Local-Only versie.
    - Pak de inhoud van het gedownloade bestand uit in deze nieuwe map `gowam`.

3. **De applicatie starten**
    - Dubbelklik in de map `gowam` op het bestand `gowam.exe` om de applicatie te starten.

4. **Gowam initialiseren**
    - Voer de **API-gebruikersnaam** en het **wachtwoord** in die in Gowam Admin zijn aangemaakt, evenals een beschrijving van het apparaat waarop Gowam is geïnstalleerd.
    - Klik op **Se connecter au cloud** om Gowam te initialiseren en ga naar het inlogscherm.

4. **Een map openen**
    - Voer de **gebruikersnaam** en eventueel het **wachtwoord** in, en selecteer de map die u wilt openen.
    - Klik op **Sign in** om toegang te krijgen tot de geselecteerde map.
