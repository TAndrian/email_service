# Projet Personnel – Plateforme d’envoi d’emails  
**Période** : Depuis Novembre 2024  
**Rôle** : Développeur Fullstack  
**Auteur** : Tahiriniaina Andrianina RAKOTOARISOA

---

## Contexte  
Dans le cadre de mes projets personnels, j'ai développé une plateforme permettant de m'envoyer des emails via un formulaire en ligne.  
L'objectif principal était de maîtriser l'ensemble du cycle de développement, de la conception jusqu'au déploiement automatisé en production, tout en garantissant une qualité de code élevée grâce à des tests et des pipelines CI/CD.  

Ce projet a également été une opportunité pour approfondir mes connaissances sur la gestion des emails en Spring Boot et sur les outils d'automatisation tels que GitHub Actions et Docker.

---

## Documentation métier  
- **Objectif fonctionnel** : permettre à l'utilisateur d’envoyer facilement des emails via une interface web simple, sans recours à un client mail externe.  
- **Utilisateurs cibles** : utilisateur individuel cherchant à envoyer rapidement des emails via un formulaire sécurisé et accessible en ligne.  
- **Valeur ajoutée** : simplification et automatisation du processus d’envoi d’emails avec contrôle total sur la gestion et la personnalisation des messages.  
- **Contraintes métiers** : fiabilité de l’envoi, garantie de la confidentialité des données, interface intuitive pour éviter toute erreur utilisateur.  

---

## Actions réalisées  

### Développement de la plateforme  
- Création d’une application backend en Spring Boot intégrant la gestion des emails avec le module Spring Email  
- Développement d’interfaces utilisateurs avec Thymeleaf pour le formulaire d’envoi  

### Tests  
- Mise en œuvre de tests unitaires et d'intégration pour valider la logique métier  
- Garantie d’une interaction correcte entre les différents modules  

### CI/CD  
- Configuration de pipelines CI/CD sur GitHub Actions  
- Automatisation du build, exécution des tests, création d’un conteneur Docker  
- Déploiement automatique sur Render.com  

---

## Résultats obtenus  
- **Plateforme fonctionnelle** : déploiement réussi d’une application robuste et fiable pour la gestion de l'envoi d’emails via interface web  
- **Qualité garantie** : taux élevé de couverture par tests unitaires et d’intégration, réduisant significativement les bugs en production  
- **Automatisation complète** : pipeline CI/CD fluide assurant des déploiements sans erreurs en production  
- **Expérience utilisateur optimisée** : interface intuitive et réactive facilitant l’envoi d’emails  

**Lien de la démo** : [https://email-service-latest.onrender.com](https://email-service-latest.onrender.com)  

---

## Environnement technique  

| Catégorie          | Technologies                                  |
|--------------------|----------------------------------------------|
| Backend            | Spring Boot, Spring Email                     |
| Frontend           | Thymeleaf                                    |
| Tests              | Mockito, JUnit, Postman                      |
| CI/CD              | GitHub Actions                              |
| Conteneurisation   | Docker                                       |
| IDE                | IntelliJ IDEA, Postman                       |
| Hébergement        | Render.com                                   |
