---
title: Instructions hébergées en ligne
permalink: index.html
layout: home
---

# MS-4008 : expérience interactive Microsoft 365 Copilot pour les cadres 

## Répertoire de contenu

Les démonstrations de ce cours sont basées sur les démonstrations du kit d’accélération [Guide de démonstration et points de discussion.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

Il est important de vous familiariser avec les démonstrations avant d’effectuer cette formation. Pour plusieurs labos, vous allez utiliser des exemples de documents et des réunions Teams et e-mails précréés.

- Préchargez tous les exemples de documents [ici](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles).
- Configurez les réunions Teams et les fils d’e-mails en suivant les instructions fournies [ici](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Familiarisez-vous avec l’expérience interactive :
    - Option 1 : [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - Option 2 : [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **NOTE :** si les particpants ne possèdent pas de licence Microsoft 365 Copilot, ceux-ci peuvent utiliser la version commerciale gratuite de l’expérience disponible à l’adresse [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE).

## Description du cours

Découvrez comment Microsoft 365 Copilot élève la productivité et l’innovation sur le lieu de travail. Cette expérience, conçue pour le chef d'entreprise moderne, fournit des indications sur l'élaboration d'invites contextuelles pour Copilot et comprend des exercices de cas d'utilisation attrayants qui démontrent une intégration transparente dans les flux de travail quotidiens.

Les principaux objectifs de cette formation sont les suivants :

- Présenter Microsoft 365 Copilot aux participants et leur apprendre comment créer une invite efficace
- Effectuer une démonstration de Microsoft 365 Copilot dans les applications Office (jusqu’à 3 démonstrations)
- Guider les participants à travers une expérience interactive
- Inviter les participants à télécharger et essayer Microsoft Copilot pour mobile

## Durée du cours (estimation) 

| # | Sujet                                 | Temps total      |
|---|---------------------------------------|-----------------|
| 1 | Présentation de Microsoft 365 Copilot | 10 minutes    |
| 2 | Guide d’élaboration d’invites efficaces à destination des cadres | 30 minutes      |
| 3 | Expérience interactive Microsoft 365 Copilot  | 20 minutes      |
|   |                                       | **Durée totale : 60 minutes** |


Les liens hypertexte vers chaque version de démonstration sont répertoriés ci-dessous.

## Démonstrations

{% assign demos = site.pages | where_exp:"page", "page.url contains ’/Instructions/Demos’" %}
| Démo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
