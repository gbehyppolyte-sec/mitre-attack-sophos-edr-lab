# 🛡️ MITRE ATT&CK Simulation with Sophos EDR

## 🎯 Objectif
Simuler des techniques d’attaque basées sur le framework MITRE ATT&CK afin d’analyser la capacité de détection et de réponse de Sophos EDR.

---

## 🧠 Contexte

MITRE ATT&CK est un référentiel de techniques et tactiques utilisées par les attaquants, basé sur des observations réelles.

👉 Il permet de :
- comprendre le comportement des attaquants  
- classer les attaques  
- améliorer la détection et la défense  

Sophos EDR s’appuie sur ce framework pour détecter et analyser les menaces sur les systèmes.

---

## ⚙️ Environnement

- Machine Windows (cible avec Sophos EDR)
- Machine Linux / Kali (attaquant)
- Sophos Central (console cloud)
- Framework MITRE ATT&CK

---

## 🛠️ Outils

- Sophos EDR (protection et détection)
- Intercept X (anti-exploit)
- MITRE CALDERA (simulation d’attaques)
- PowerShell (exécution des agents)

---

## 🔍 Fonctionnement

### 🔹 MITRE ATT&CK
- Organisation en **tactiques** (objectifs)
- Chaque tactique contient des **techniques**
- Permet de modéliser les attaques réelles

---

### 🔹 Sophos EDR

- Protection des terminaux via des agents  
- Analyse comportementale des menaces  
- Détection basée sur MITRE ATT&CK  
- Réponse automatique (blocage, alerte, isolation)

---

## 🧪 Mise en pratique

### 1️⃣ Déploiement de Sophos EDR

- Installation de l’agent sur la machine Windows  
- Connexion automatique à Sophos Central  
- Protection active (anti-malware, anti-phishing)

---

### 2️⃣ Simulation d’attaque avec CALDERA

- Déploiement d’un agent sur la machine cible  
- Création d’opérations (attaques simulées)  
- Sélection de tactiques et techniques MITRE  

👉 Exemple :
- Discovery (reconnaissance)
- Network Service Scanning (T1046)

---

### 3️⃣ Détection avec Sophos

- Analyse via **Threat Analysis Center**
- Utilisation de **Live Discover**
- Filtrage des événements selon MITRE ATT&CK

👉 Résultat :
- identification des techniques utilisées  
- détails des processus exécutés  
- visualisation des comportements suspects  

---

## 🚨 Réponse aux incidents

Sophos permet :

- suppression automatique des menaces  
- analyse détaillée des processus  
- visualisation via graphe  
- isolation de la machine infectée  

👉 Exemple :
- détection d’un comportement malveillant  
- suppression du fichier suspect  
- isolement de la machine  

---

## 📊 Analyse

- Détection efficace des techniques MITRE  
- Visibilité complète sur les actions malveillantes  
- Corrélation entre attaque simulée et alerte  

---

## 🛡️ Apports

Ce projet montre :

- l’intérêt de MITRE ATT&CK pour la détection  
- l’efficacité d’un EDR dans un contexte réel  
- l’importance de la surveillance continue  

---

## 📊 Compétences

- EDR / XDR  
- Analyse de logs et détection  
- Simulation d’attaques (Red Team)  
- Investigation (Blue Team)  
- Framework MITRE ATT&CK  

---

## 📎 Conclusion

Ce projet met en évidence l’efficacité de Sophos EDR pour détecter et analyser des attaques basées sur MITRE ATT&CK.

Il montre également l’importance des outils de détection pour identifier rapidement les comportements malveillants et réagir efficacement.
