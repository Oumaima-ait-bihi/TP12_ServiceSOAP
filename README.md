# TP 12 : Service SOAP avec Apache CXF

Ce TP a pour objectif de mettre en œuvre un service web SOAP à l’aide de la bibliothèque **Apache CXF**, en utilisant une architecture basée sur les interfaces WSDL.

## Capture d’écran 1 : Requête et réponse pour `FindPerson`

![Requête et réponse FindPerson](https://i.imgur.com/your-image-url-1.png)

> Cette capture montre une requête SOAP envoyée au service pour récupérer les informations d’une personne (`id=20`). La réponse contient l’âge, l’identifiant et le nom de la personne.

---

## Capture d’écran 2 : Requête et réponse pour `SayHello`

![Requête et réponse SayHello](https://i.imgur.com/your-image-url-2.png)

> Ici, le service SOAP répond à une requête `SayHello` avec un message personnalisé : `"Bonjour, oumaima"`, démontrant le bon fonctionnement de l’interface.

---

## Technologies utilisées
- **Apache CXF** : Pour la création du service SOAP
- **Java** : Langage de développement
- **Maven** : Gestion des dépendances
- **SoapUI** ou équivalent : Pour tester les services

---

## Comment exécuter le projet
1. Clonez le dépôt
2. Exécutez `mvn clean install`
3. Lancez l’application
4. Accédez à `http://localhost:8080/services/hello` pour tester les services

---

✅ Ce TP illustre les bases de la communication SOAP, largement utilisée dans les systèmes d’entreprise.
