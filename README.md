# 🔐 Déchiffreur (Go)

Petite application web en **Go** (`net/http`) qui déchiffre un texte chiffré par
un **décalage de César de +2 lettres** : chaque lettre est ramenée 2 positions en
arrière dans l'alphabet (en conservant la casse et les caractères non alphabétiques).

## 🚀 Lancer

Prérequis : [Go](https://go.dev/dl/) installé.

```bash
go run .
```
Puis ouvrir **http://localhost:8080/home**, saisir le code à déchiffrer et valider.

## 🛣️ Routes

| Route | Méthode | Description |
|-------|---------|-------------|
| `/home` | GET | Formulaire de saisie |
| `/code/treatment` | POST | Renvoie le texte déchiffré |

## 📁 Structure

```
.
├── main.go              # Serveur + fonction de déchiffrement
├── templates/home.html  # Formulaire
├── go.mod
└── README.md
```

## 👨‍💻 Auteur

Louey Barbirou — Ynov.
