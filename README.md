# CVMELE-ON : Adaptive RAG Agent for Job Applications 🦎

![Status - Operational](https://img.shields.io/badge/Status-Operational-brightgreen.svg)
![Orchestration - n8n](https://img.shields.io/badge/Orchestrator-n8n-orange.svg)
![AI - OpenAI](https://img.shields.io/badge/AI-OpenAI_GPT--4o-blue.svg)
![Interface - Telegram](https://img.shields.io/badge/Interface-Telegram_API-2CA5E0.svg)

## 🎯 1. L'Enjeu (Business & Personal Branding)
Le processus de candidature est souvent perçu comme une tâche de volume au détriment de la qualité. 
* **Problématique** : Envoyer des candidatures génériques réduit drastiquement le taux de réponse (conversion). Personnaliser manuellement chaque dossier prend des heures.
* **Philosophie "Be Water"** : Créer un agent capable de s'adapter instantanément à l'ADN d'une entreprise et d'une fiche de poste, automatisant **95% du cycle de candidature** tout en conservant une touche humaine chirurgicale.

## 💡 2. La Solution (Product Workflow)
CVMELE-ON n'est pas un simple bot, c'est un assistant RH personnel qui gère l'intégralité du tunnel :
1. **Sourcing & Analyse** : Extraction des mots-clés et de la culture d'entreprise depuis une URL ou un PDF.
2. **Génération RAG** : Croisement des données du candidat (base de connaissances) avec les exigences du poste pour générer des documents uniques.
3. **Validation Humaine** : Notification via Telegram pour revue et ajustement final avant envoi.
4. **Suivi RH** : Automatisation des rappels et suivi des interactions dans un CRM dédié.



## 🛠 3. L'Exécution (Technique & Infrastructure)
Le projet est déployé de manière robuste sur un serveur dédié, utilisant une architecture de micro-services automatisés.
* **Orchestrateur** : **n8n** (self-hosted) pour la gestion des workflows asynchrones et des webhooks.
* **Moteur IA** : **OpenAI (GPT-4o)** avec une architecture **RAG** (Retrieval-Augmented Generation) pour garantir la véracité des informations professionnelles.
* **Interface de Contrôle** : **Telegram API** servant de tableau de bord mobile pour la validation en temps réel.

### Pourquoi n8n ?
J'ai choisi l'orchestration via n8n pour garantir une **maintenabilité maximale** et une capacité à pivoter (ajouter de nouveaux nœuds) sans réécrire le coeur logique du système. Cela démontre une approche de **Product Engineer** axée sur la rapidité de déploiement (Time-to-Market).

## 🚀 4. Impact & Compétences Mobilisées
* **Hard Skills** : Orchestration de flux (n8n), Intégration d'APIs tierces, Prompt Engineering avancé, Déploiement sur serveur (Docker/Linux), RAG Systems.
* **Soft Skills** : Vision stratégique (optimisation de conversion), Priorisation des fonctionnalités, Esprit d'innovation "Be Water".

---
*Projet développé par **Fodé DIAKHABY** - Conçu pour l'efficience, bâti pour l'adaptation.*
