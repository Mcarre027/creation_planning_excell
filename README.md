
# 🗓️ Générateur de Planning Hebdomadaire en Python

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XIRVAMfSvox2dHlSHlaN4jH17fWHYl0-?authuser=0#scrollTo=jsp-goIQ_8e3)

Créez un planning propre et organisé de votre semaine **en moins de 5 minutes** grâce à Python et Excel.

---

## 📌 Objectif

Ce projet vous permet de générer automatiquement un fichier Excel de planning hebdomadaire (de **8h à 18h**, du **lundi au dimanche**) avec :

- ✅ Un tableau clair, sans cellule vide ni "NaN"  
- ✅ Des cases bordées, centrées et prêtes à imprimer ou partager  
- ✅ Une personnalisation rapide des créneaux (réunions, sport, projets perso...)

---

## 🧰 Technologies utilisées

- Python  
- pandas  
- openpyxl (pour le formatage Excel)

---

## 🚀 Lancer le script

### 1. Cloner le repo

```bash
git clone https://github.com/votre-utilisateur/Planning-Hebdo.git
cd Planning-Hebdo
```

### 2. Installer les dépendances

```bash
pip install pandas openpyxl
```

### 3. Lancer le script

```bash
python generateur_planning.py
```

➡️ Un fichier `Planning_Hebdomadaire_CleanFinal.xlsx` sera généré dans le dossier courant.

---

## ✏️ Personnaliser votre planning

Dans le script, modifiez les créneaux en remplaçant ou ajoutant des lignes comme :

```python
planning.loc[planning["Heures"] == "9h", "Lundi"] = "Réunion équipe"
planning.loc[planning["Heures"] == "14h", "Mardi"] = "Sport"
```

💡 Astuce : gardez le format `"Heures", "Jour"` pour ajouter vos propres événements.

---

## 📄 Fichier généré

- `Planning_Hebdomadaire_CleanFinal.xlsx`  
Un fichier Excel **propre, centré, bordé et prêt à l’usage**.

---

## 🧠 Pourquoi ce projet ?

Créer son planning manuellement dans Excel prend du temps.  
Avec ce script Python, vous gagnez en :

- ✔️ Clarté  
- ✔️ Structure  
- ✔️ Efficacité ⏱️

---

## ✅ Idéal pour :

- Organiser votre semaine personnelle ou professionnelle  
- Intégrer à vos routines de productivité  
- Générer des plannings récurrents automatiquement

---

## 📬 Contact

Une question, une amélioration, une idée ?  
📩 Créez une issue ou contactez-moi sur [LinkedIn](https://www.linkedin.com/in/mathieucarre/)

