- RoGAI
- Simple AI chatbot to get assistance on specific topics : RoGAI is a RAG.

# 🤖 RoGAI — Assistant IA basé sur le RAG

**RoGAI** est un assistant conversationnel basé sur une architecture **Retrieval-Augmented Generation (RAG)**. Le projet explore la mise en place d'un système capable de rechercher des informations pertinentes dans un corpus documentaire, puis de les utiliser comme contexte pour générer des réponses en langage naturel.

Le prototype s'appuie sur un corpus de **quatre livres** issus de l'univers *Les Résonants*. L'utilisateur peut poser une question en langage naturel et l'assistant recherche les passages pertinents dans les documents avant de générer une réponse contextualisée.

## 🎯 Objectif

L'objectif du projet est de mettre en pratique les principales étapes d'un pipeline RAG :

* ingestion et préparation de documents ;
* découpage du contenu en passages exploitables ;
* représentation des contenus pour la recherche sémantique ;
* recherche des passages pertinents ;
* construction du contexte transmis au modèle ;
* génération d'une réponse en langage naturel ;
* intégration dans une interface interactive avec **Gradio**.

## 🧠 Fonctionnement

Le fonctionnement général du système peut être résumé ainsi :

**Question utilisateur → Recherche documentaire → Récupération du contexte pertinent → Génération de la réponse**

Contrairement à un chatbot reposant uniquement sur les connaissances générales d'un modèle de langage, RoGAI utilise le corpus documentaire fourni comme source de contexte pour répondre aux questions.

## 📚 Corpus documentaire

Le prototype utilise quatre ouvrages :

* *Kairo et l'Engrenage Écarlate*
* *Wambo, Esprit de la Canopée*
* *Les Gardiennes du Noyau*
* *L'Étoile Bisou, Vaisseau du Cœur*

Le système peut ainsi être utilisé pour explorer le contenu des ouvrages à travers des questions posées en langage naturel.

## 🛠️ Technologies

* **Python**
* **RAG — Retrieval-Augmented Generation**
* **Traitement de documents**
* **Recherche sémantique**
* **Modèles de langage**
* **Gradio**
* **Jupyter Notebook**

## 💡 Ce que ce projet met en pratique

Ce projet m'a permis de travailler sur la conception d'une application IA allant au-delà de la simple génération de texte, en intégrant une étape de **recherche documentaire avant la génération**.

Il constitue également une base pour expérimenter par la suite des systèmes RAG plus avancés : corpus plus importants, différentes stratégies de découpage, amélioration de la pertinence des résultats, évaluation des réponses et intégration dans une application web ou une API.

## 🚀 Démonstration

L'application fournit une interface Gradio permettant de poser directement des questions au système et d'observer les réponses générées à partir du corpus documentaire.

> Projet réalisé dans le cadre de mon apprentissage autour des architectures RAG et des applications basées sur les modèles de langage.
