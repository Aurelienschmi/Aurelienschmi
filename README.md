# Durcissement Docker & Observabilité Infrastructure

> Sécurisation d'environnements Docker en production et mise en place de supervision Prometheus/Grafana — missions courtes, périmètre cadré.

## Ce que je livre

**Audit de sécurité d'une stack Docker**
Cartographie des surfaces d'exposition (daemon, réseaux, volumes, images), rapport de vulnérabilités et plan de remédiation priorisé par criticité — livré exploitable, pas une liste de recommandations génériques.

**Durcissement d'infrastructure conteneurisée**
Configuration du daemon Docker selon le CIS Benchmark, gestion des secrets hors image, segmentation réseau, réduction des privilèges (rootless, capabilities, read-only filesystems), images minimalistes et reproductibles.

**Mise en place de supervision Prometheus / Grafana**
Déploiement de la stack de collecte et de visualisation, dashboards opérationnels adaptés à l'infrastructure réelle (pas de templates génériques), règles d'alerting configurées sur des seuils pertinents.

**Administration Linux orientée fiabilité**
Durcissement système, gestion des accès et des permissions, journalisation centralisée — en support des deux points précédents.

*Kubernetes, Terraform, Ansible et CI/CD : montée en compétence en cours, hors périmètre des missions proposées aujourd'hui.*

## Pourquoi ce périmètre restreint

Un audit Docker ou une stack de monitoring mal calibrée coûte plus cher à corriger qu'à ne pas avoir. Je préfère maîtriser un périmètre précis — Docker, monitoring, Linux — plutôt que d'afficher une familiarité de façade avec quinze technologies.

Concrètement : ce que je propose, je l'ai réellement mis en œuvre et je peux en défendre chaque choix technique. Ce que je ne maîtrise pas encore, je ne le vends pas. C'est un engagement sur la fiabilité du résultat, pas sur l'étendue du catalogue.

## Projets

- 📝 Blog technique — retours d'expérience sur le durcissement Docker et la mise en place de monitoring : *[à compléter]*
- 🗂️ [Portfolio](https://aurelien-schmieder.vercel.app/) — synthèse des interventions et cas d'usage
- 🐳 Repos Docker / monitoring — configurations de référence, dashboards Grafana, exemples de durcissement : *[à compléter]*

## Missions & contact

Interventions ponctuelles et cadrées dans le temps (audit, durcissement, mise en place de dashboards) — sans astreinte ni suivi continu.

Pour un échange sur une mission : [portfolio](https://aurelien-schmieder.vercel.app/), [LinkedIn](https://www.linkedin.com/in/aurelien-schmieder-0017391ab) ou une [issue](../../issues) sur ce dépôt.
