🗓️ Générateur de Planning Hebdomadaire en Python
Créez un planning propre et organisé de votre semaine en moins de 5 minutes grâce à Python et Excel.

📌 Objectif
Ce projet vous permet de générer automatiquement un fichier Excel de planning hebdomadaire (de 8h à 18h, du lundi au dimanche) avec :

Un tableau clair, sans cellule vide ni "NaN"

Des cases bordées, centrées et prêtes à imprimer ou partager

Une personnalisation rapide des créneaux (réunions, sport, projets perso...)

🧰 Technologies utilisées
Python

pandas

openpyxl (formatage Excel)

🚀 Lancer le script
Cloner le repo :

bash
Copier
Modifier
git clone https://github.com/votre-utilisateur/Planning-Hebdo.git
cd Planning-Hebdo
Installer les dépendances :

bash
Copier
Modifier
pip install pandas openpyxl
Lancer le script dans un notebook ou un environnement Python :

bash
Copier
Modifier
python generateur_planning.py
Un fichier Planning_Hebdomadaire_CleanFinal.xlsx sera généré dans le dossier courant.

✏️ Personnaliser votre planning
Dans le script, vous pouvez modifier facilement les créneaux comme ceci :

python
Copier
Modifier
planning.loc[planning["Heures"] == "9h", "Lundi"] = "Réunion équipe"
planning.loc[planning["Heures"] == "14h", "Mardi"] = "Sport"
💡 Conseil : gardez le format "Heures", "Jour" pour modifier vos propres rendez-vous.

📷 Aperçu du rendu final
<img src="Planning_Hebdo_Visuel_Clean.png" width="700"/>
📄 Fichier généré
Planning_Hebdomadaire_CleanFinal.xlsx : fichier Excel propre, formaté, prêt à l’emploi.

🧠 Pourquoi ce projet ?
Créer son planning manuellement dans Excel prend du temps.
Avec ce script Python, vous gagnez en clarté, en structure, et surtout… en temps ⏱️

✅ Idéal pour :
Organiser votre semaine pro ou perso

Intégrer à vos routines productivité

Générer des plannings récurrents automatiquement

📬 Contact
Un retour, une idée d’amélioration ou une suggestion ?
N'hésitez pas à créer une issue ou à me contacter sur LinkedIn

