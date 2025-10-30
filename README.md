# HR Association - Application de Gestion des Employés

Une application Spring Boot pour la gestion des employés, composée d'une API REST et d'une interface web.

## 🚀 Fonctionnalités

- **API REST** : Gestion complète des employés (CRUD)
- **Interface Web** : Interface utilisateur intuitive
- **Base de Données** : H2 en mémoire avec console d'administration
- **Architecture** : Multi-modules Maven

## 📋 Prérequis

- Java 17
- Maven 3.6+
- Git

## 🛠️ Installation

### 1. Cloner le projet
```bash
git clone https://github.com/MariemMhadhbii/HR-Association.git
cd HR-Association
2. Construire le projet
bash
mvn clean install
🚀 Démarrage
API (Backend)
bash
cd api
mvn spring-boot:run
Port : 9000

URL : http://localhost:9000

Webapp (Frontend)
bash
cd webapp  
mvn spring-boot:run
Port : 8080

URL : http://localhost:8080

📊 Accès aux services
Console H2 Database
URL : http://localhost:9000/h2-console

JDBC URL : jdbc:h2:mem:testdb

Username : sa

Password : (vide)

API Endpoints
GET /employees - Liste tous les employés

GET /employees/{id} - Obtenir un employé par ID

POST /employees - Créer un nouvel employé

PUT /employees/{id} - Modifier un employé

DELETE /employees/{id} - Supprimer un employé

🏗️ Architecture
text
HR-Association/
├── api/                 # Module API REST
│   ├── src/
│   └── pom.xml
├── webapp/              # Module Interface Web
│   ├── src/
│   └── pom.xml
└── README.md
💾 Technologies Utilisées
Backend : Spring Boot 3.2.0, Spring Data JPA, Hibernate

Frontend : Spring MVC, Thymeleaf, Bootstrap

Base de Données : H2 Database

Build Tool : Maven

Java Version : 17

👥 Données de Test
L'application charge automatiquement des données de test :

Laurent GINA (laurentgina@mail.com)

Sophie FONCE (sophiefonce@mail.com)

Agathe FEELING (agathefeeling@mail.com)

🔧 Configuration
Les fichiers de configuration se trouvent dans src/main/resources/application.properties

📝 License
Ce projet est sous licence MIT.

👤 Auteur
Mariem Mhadhbi

GitHub: @MariemMhadhbii

Email: mhadhbiimariem@gmail.com
