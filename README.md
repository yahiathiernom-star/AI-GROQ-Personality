# AI-GROQ-Personality

Un chatbot conversationnel développé en Python utilisant l'API Groq. Le programme permet d'interagir avec un modèle de langage en définissant une personnalité et en générant des réponses adaptées aux messages de l'utilisateur.

## Fonctionnalités

- Conversation en temps réel
- Utilisation de l'API Groq
- Personnalité personnalisable du chatbot
- Gestion sécurisée de la clé API avec un fichier `.env`
- Projet simple et facilement extensible

## Technologies

- Python 3
- Groq API
- python-dotenv

## Structure du projet

```text
AI-GROQ-Personality/
│── .env
│── .gitignore
│── main.py
│── README.md
│── requirements.txt
│── env/
```

## Installation

### 1. Cloner le projet

```bash
git clone https://github.com/yahiathiernom-star/AI-GROQ-Personality
cd AI-GROQ-Personality
```

### 2. Créer un environnement virtuel

```bash
python -m venv env
```

### Windows

```bash
env\Scripts\activate
```

### macOS / Linux

```bash
source env/bin/activate
```

### 3. Installer les dépendances

```bash
pip install -r requirements.txt
```

## Configuration

Créer un fichier `.env` :

```env
GROQ_API_KEY=Votre_Clé_API
```

## Lancer le projet

```bash
python main.py
```

## Exemple

```text
Vous : Bonjour

Assistant : Bonjour ! Comment puis-je vous aider aujourd'hui ?

Vous : Qui es-tu ?

Assistant : Je suis un assistant conversationnel utilisant l'API Groq.
```

## Dépendances

- groq
- python-dotenv

Pour générer le fichier des dépendances :

```bash
pip freeze > requirements.txt
```

## Améliorations possibles

- Ajouter une interface graphique
- Sauvegarder l'historique des conversations
- Choisir différents modèles Groq
- Ajouter une mémoire de conversation
- Déployer l'application sur le Web

## Auteur

Yahia Thierno Maiga
Étudiant en Data & IA à HETIC