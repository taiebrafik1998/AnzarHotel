
# 🏨 AnzarHotel – Gestion d'Hôtel en Microservices

Bienvenue dans **AnzarHotel**, une application de gestion d’hôtel complète et modulaire basée sur une architecture microservices. Ce projet a pour but d'apprendre toutes les technologies modernes utilisées en entreprise tout en construisant une application professionnelle.

## 🚀 Objectifs du projet

- Gérer les réservations, chambres, clients, factures, services de restauration
- Avoir plusieurs interfaces (admin, réception, commis, manager)
- Utiliser une architecture microservices conteneurisée
- Mettre en place la recherche, le monitoring et le CI/CD
- Apprendre à utiliser Git, Docker, Django, Spring Boot, Next.js, Elasticsearch, Prometheus, GitHub Actions…

## 🧱 Stack technique

- **Frontend** : Next.js, TailwindCSS, shadcn/ui
- **Backend** : Django, Spring Boot, Symfony, FastAPI
- **Base de données** : PostgreSQL, MySQL, MongoDB
- **Communication interservices** : REST + RabbitMQ
- **Conteneurs** : Docker + Docker Compose
- **Recherche** : Elasticsearch + Kibana
- **Monitoring** : Prometheus + Grafana + cAdvisor
- **CI/CD** : GitHub Actions
- **Sécurité** : JWT

## 📁 Structure du projet

```
anzarhotel/
├── docker/                  # Fichiers Docker techniques (ES, Prometheus…)
├── services/                # Tous les microservices (chambre, client, etc.)
├── frontend/                # Interfaces Next.js (admin, resto, réception…)
├── monitoring/              # Fichiers de configuration Prometheus, Grafana
├── docker-compose.yml       # Lancement global
└── README.md
```

## 📦 Microservices prévus

- chambre-service (Django)
- reservation-service (Django + RabbitMQ)
- client-service (Spring Boot)
- facturation-service (Django)
- notification-service (Spring Boot)
- auth-service (Django + JWT)
- roomservice-service (Spring Boot)
- resto-service (Spring Boot)
- vente-service (Django)
- reporting-service (FastAPI)
- staff-service (Symfony)
- reception-service (Django)
- gateway-service (NGINX ou Express)

## 📊 Interfaces prévues

- `admin-dashboard` – pour la gestion complète
- `interface-resto` – pour les commis de rang
- `interface-manager` – pour les maîtres d’hôtel
- `interface-reception` – pour les réceptionnistes

## 👨‍💻 Auteur

Rafik Taieb 
email: mtaieb.rafik@gmail.com


