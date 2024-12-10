# Spring Boot gRPC Project

Ce projet est une implémentation utilisant **Spring Boot** et **gRPC** pour créer un service d’API rapide, performant et extensible. Ce document explique comment configurer, exécuter et utiliser ce projet.

## Prérequis

Avant de commencer, assurez-vous d’avoir les éléments suivants installés sur votre machine :

- **Java JDK** (version 17 ou supérieure recommandée)
- **Maven** (pour la gestion des dépendances et la compilation)
- **Protoc** (compiler protocole buffer pour gRPC)
- **Git** (facultatif pour cloner ce répertoire)

## Installation

1. Clonez le projet depuis ce dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/nom-du-repo.git
   cd nom-du-repo
   ```

2. Générez les fichiers de stubs gRPC :
   ```bash
   protoc --java_out=src/main/java --grpc-java_out=src/main/java -I=src/main/proto src/main/proto/*.proto
   ```

3. Compilez le projet avec Maven :
4. 
   ```bash
   mvn clean install
   ```

https://github.com/user-attachments/assets/339bae30-01da-48ef-880e-43e2cbf8d43a



