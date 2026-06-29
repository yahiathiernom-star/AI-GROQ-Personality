# AI-GROQ-Personality

# Chatbot IA avec Python & Groq API

Un chatbot conversationnel développé en **Python** utilisant l'API **Groq** pour générer des réponses grâce à un modèle de langage.

## Présentation

Ce projet est un chatbot en ligne de commande capable de répondre aux questions de l'utilisateur en utilisant l'API Groq. Il envoie les messages au modèle de langage et affiche la réponse dans le terminal.

## Fonctionnalités

- Conversation en temps réel
- Génération de réponses via l'API Groq
- Utilisation d'une clé API sécurisée avec un fichier `.env`
- Développé entièrement en Python
- Architecture simple et facilement extensible

## Technologies utilisées

- Python 3
- Groq API
- python-dotenv
- groq

## Structure du projet

```text
chatbot-groq/
│── chatbot.py
│── .env
│── requirements.txt
│── README.md
```

## Installation

### 1. Cloner le dépôt

```bash
git clone https://github.com/yahiathiernom-star/AI-GROQ-Personality
cd AI-GROQ-Personality
```

### 2. Créer un environnement virtuel

```bash
python -m venv .venv
```

#### Windows

```bash
.venv\Scripts\activate
```

#### macOS / Linux

```bash
source .venv/bin/activate
```

### 3. Installer les dépendances

```bash
pip install -r requirements.txt
```

## Configuration

Créer un fichier `.env` à la racine du projet :

```env
API_KEY=votre_cle_api
```

## Lancement

Exécuter la commande suivante :

```bash
python chatbot.py
```

## Exemple d'utilisation

```text
Vous : Bonjour

Bot : Bonjour ! Comment puis-je vous aider aujourd'hui ?

Vous : Explique-moi le machine learning.

Bot : Le machine learning est une branche de l'intelligence artificielle...
```

## Dépendances

Les principales bibliothèques utilisées sont :

- groq
- python-dotenv

Pour générer le fichier `requirements.txt` :

```bash
pip freeze > requirements.txt
```

## Améliorations possibles

- Ajouter une interface graphique avec Tkinter ou CustomTkinter
- Développer une interface web avec Flask ou Streamlit
- Sauvegarder l'historique des conversations
- Ajouter une mémoire de conversation
- Permettre le choix du modèle Groq
- Déployer l'application sur un serveur

## Auteur

Yahia Thierno Maiga

Étudiant en Data & IA.