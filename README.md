# n8n Workflow Collection

> 🚀 **Voici les workflows que j'ai conçus ces deux derniers jours, tous testés et opérationnels sur ma propre instance n8n.**  
> Grâce à ces automatisations, je peux désormais orchestrer mes tâches du quotidien et des projets personnels de façon totalement no-code.

---

## 🖼️ Présentation visuelle

![n8n overview](la situation de workespace n8n.jpg)
*Vue d'ensemble de mon espace n8n et de mes workflows actifs.*

---

## 1. Recommandation automatique de vidéos MrBeast sur Discord

**Automated MrBeast YouTube video recommendations sent to Discord**

- Récupération des dernières vidéos de MrBeast via RSS et Google API
- Génération d’une recommandation personnalisée avec GPT-4.1 mini
- Envoi automatique sur un serveur Discord chaque semaine

![mrbeast_workflow](Gh6bC7Xx8GWmYsAxJmtEpF.png)
*Schéma du workflow n8n.*

**Exemple de message envoyé automatiquement sur Discord :**

![Résultat Discord](discord_screenshot.jpg)

---

## 2. Assistant personnel Google Sheet → Email

**Personal planner assistant: Google Sheet to daily email**

- Génération d’une recommandation personnalisée à l’aide de DeepSeek
- Lecture quotidienne des plannings depuis Google Sheet
- Sélection automatique des meilleures suggestions de sortie du jour
- Envoi par email chaque matin avec résumé personnalisé

![Résultat mail](mail resultat.jpg)
![workflow_n8n](b5d0d9c3-89d6-4516-afd7-cf8ec1b96a11.png)
*Exemple de mail reçu et schéma du workflow associé.*

**📋 Base d'activités d'étudiant à Pau**  
Toutes les activités sont maintenues dans un Google Sheet : météo idéale, durée, type, lieu, etc.  
Ce tableau dynamique permet à l'agent AI d'adapter chaque recommandation du matin selon la météo et l’emploi du temps du jour.

![activites_sheet](activites.jpg)

---

## 💡 Importer les workflows

1. Télécharger le fichier `.json` correspondant
2. Aller sur votre interface n8n → “Importer un workflow”
3. Uploader le fichier
4. Configurer vos clés API, webhooks Discord, ou accès email selon besoin

---

**Auteur / Author :**  
Li Jiale  
ESIEE-IT, Alternance Big Data & IA, 2025

---

_Contactez-moi pour toute question, suggestion ou collaboration !_
