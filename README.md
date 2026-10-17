# 🚗 AutoLoc

> Plateforme de gestion de location de véhicules multi-agences

![Java](https://img.shields.io/badge/Java-17+-orange?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.1.1-brightgreen?logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-database-4479A1?logo=mysql&logoColor=white)

## 📖 Description

Application Spring Boot pour la gestion d'un service de location de véhicules : véhicules, clients, employés, réservations, contrats, paiements, équipements et maintenances.

Projet développé dans le cadre du module ASI — ESPRIT.

## 👥 Acteurs

- 🧑 Client
- 🧑‍💼 Agent d'agence
- 👔 Responsable d'agence
- 🛡️ Administrateur

## 🛠️ Stack technique

Java 17+ · Spring Boot · Spring Data JPA · MySQL · Lombok · Maven

## 🏗️ Architecture

tn.esprit.autoloc

├── domain → Entités JPA

├── repository → Interfaces Spring Data JPA

├── service → Logique métier

├── exception → Exceptions métier

└── web.controller → Contrôleurs REST
