# La veille sur Power BI 
**Power BI (Business Intelligence)** est une suite d'outils de visualisation de données développée par Microsoft, permettant aux utilisateurs de transformer des données brutes en informations exploitables et facilement compréhensibles à travers des rapports et des tableaux de bord interactifs. C’est une solution de business intelligence accessible aux utilisateurs, qu'ils soient débutants ou expérimentés, pour analyser et visualiser des données issues de différentes sources.

Voici les principales fonctionnalités et composants de Power BI :
## Power BI Desktop :

C’est une application gratuite pour les utilisateurs Windows permettant de créer des rapports et des tableaux de bord. Vous pouvez importer des données de plusieurs sources (Excel, bases de données, fichiers CSV, etc.), les transformer et créer des visualisations interactives.

## Power BI Service (Power BI Online) :

C'est une version cloud de Power BI qui permet de partager, publier et collaborer sur des rapports et des tableaux de bord. Il offre des fonctionnalités telles que la planification des actualisations de données, l’accès à des rapports en temps réel, et l’intégration avec d'autres services cloud de Microsoft comme Azure.

## Power BI Mobile :

Il existe des applications mobiles (iOS et Android) pour consulter des rapports et tableaux de bord Power BI depuis un smartphone ou une tablette, ce qui permet de suivre les données en temps réel en déplacement.

## Power BI Gateway :

Cela permet de connecter Power BI aux sources de données locales (sur site), de manière sécurisée, pour actualiser les données en temps réel ou à intervalle programmé.

## Power BI Report Server :

Pour les entreprises qui préfèrent une solution sur site plutôt que cloud, Power BI Report Server permet de publier, partager et gérer des rapports Power BI dans un environnement local.

## Intégration de l'IA :

Power BI utilise des capacités d'intelligence artificielle (IA) pour aider les utilisateurs à identifier des tendances ou des modèles dans les données, notamment avec des outils comme le Q&A (interroger les données en langage naturel) ou les visuels préconçus.

### Principaux avantages de Power BI :
Accessibilité : Il est accessible aux utilisateurs sans compétences techniques avancées en matière de codage ou de développement de logiciels.

**Visualisation interactive** : Vous pouvez créer des graphiques et des visuels interactifs (courbes, cartes géographiques, histogrammes, etc.), permettant de mieux comprendre les données.

**Connectivité** : Power BI permet de se connecter à une large gamme de sources de données, tant locales que dans le cloud (Excel, SQL Server, Google Analytics, Salesforce, etc.).

**Partage et collaboration** : Une fois que vous avez créé vos rapports, vous pouvez facilement les partager avec des collègues ou des parties prenantes via Power BI Service, en offrant un accès sécurisé à vos visualisations.

**Mise à jour en temps réel** : Les rapports peuvent être mis à jour en temps réel grâce à l'intégration des données en temps réel, ce qui permet une prise de décision plus rapide et basée sur des données actualisées.

**En résumé** :
Power BI est un outil puissant de visualisation et d’analyse des données qui permet aux entreprises de prendre des décisions basées sur des données précises et actuelles. Son interface intuitive et ses capacités de création de rapports interactifs en font un choix populaire pour les utilisateurs cherchant à extraire de la valeur des données sans avoir besoin de compétences techniques approfondies.
__________________________________________________________
# 🩸 Dr Death – Analyse des crimes de Harold Shipman avec Power BI

## 📌 Présentation du projet

Harold Shipman était un médecin britannique accusé d’avoir tué plus de 215 patients entre 1975 et 1998. Ce projet vise à **analyser les données de ses victimes** à travers un tableau de bord interactif créé avec **Microsoft Power BI**.

L'objectif principal est de répondre à la problématique :

> **Quels types de personnes Harold Shipman a-t-il assassinées, et quand sont-elles mortes ?**

---

## 🔍 Veille technologique sur Power BI

### ![Titre - Veille Technologique](./images/veille-titre.png)

---

### Qu’est-ce que Power BI ?

Power BI est un logiciel développé par Microsoft qui permet de connecter, transformer, analyser et visualiser des données sous forme de tableaux de bord dynamiques.

---

### Présentation générale  
![Définition + Avantages + Inconvénients](./images/powerbi-overview.png)

---

### Schéma de fonctionnement  
![Fonctionnement global de Power BI](./images/schema-fonctionnement.png)

---

### Processus standard Power BI  
![Étapes Power BI : Import ➝ Transform ➝ Visualize](./images/import-transform-visualize.png)

---

### Étapes du projet "Dr Death"  
![Étapes spécifiques Dr Death](./images/dr-death-steps.png)

---

### Avantages de Power BI  
![Avantages de Power BI](./images/avantages-powerbi.png)

---

### Inconvénients de Power BI  
![Inconvénients de Power BI](./images/inconvenients-powerbi.png)

---

### Fonctionnalités principales  
![Fonctionnalités Power BI](./images/fonctionnalites-powerbi.png)

---

### Types de visualisations  
![Types de graphiques dans Power BI](./images/types-visualisations.png)

---

### Types de données compatibles  
![Types de données Power BI](./images/types-donnees.png)

---

## 📁 Fichiers utilisés

- `shipman-confirmed-victims.csv` : liste des victimes, avec nom, âge, date, lieu de décès, etc.
- `shipman-times-comparison.csv` : comparaison des horaires de décès entre Shipman et d'autres médecins

---

## 🧼 Nettoyage des données (Power Query)

- Vérification et correction des formats de dates (`dateOfDeath`, `yearOfDeath`)
- Suppression des valeurs manquantes
- Conversion de colonnes (`Age`, `gender2`, `PlaceofDeath`) pour l’analyse

---

## 📊 Visualisations créées

1. **Histogramme : nombre de victimes par tranche d’âge**  
2. **Graphique : évolution des décès par année**  
3. **Comparaison des heures de décès (Shipman vs autres médecins)**  
4. **Répartition des victimes par genre**  
5. **Heatmap des décès par mois/trimestre (bonus)**

> *Toutes les visualisations sont visibles dans le fichier `.pbix` ou ci-dessous en capture d’écran.*

---

## 📸 Captures d’écran des Dashboards

*(Ajoute ici tes captures de Power BI en format image, par exemple :)*

- ![Graphique âges](./images/graph-age.png)
- ![Heures de décès](./images/graph-hours.png)
- ![Décès par année](./images/graph-year.png)

---

## ✅ Conclusion

L’analyse révèle plusieurs éléments importants :
- La majorité des victimes étaient **des femmes âgées entre 65 et 85 ans**
- Les décès surviennent souvent en **après-midi (14h-17h)**
- Shipman modifiait les dossiers médicaux peu de temps après les décès
- Des anomalies statistiques (fréquence, heure, profil des patients) auraient pu **révéler ses meurtres plus tôt**

Power BI a permis de mettre en évidence ces tendances de manière **intuitive, rapide et professionnelle**.

---

## 🧠 Compétences mobilisées

- Data Analysis
- Power BI (Data Import, Query, DAX, Visualizations)
- Data Cleaning
- Visual Storytelling
- Git & GitHub

---

## 🔗 Références

- [NewScientist – Statistics could have spotted mass murderer](https://www.newscientist.com/article/dn1724-statistics-could-have-spotted-mass-murderer/)
- [Microsoft Power BI Documentation](https://learn.microsoft.com/fr-fr/power-bi/)
- [Tutoriel vidéo YouTube – Débuter avec Power BI](https://www.youtube.com/watch?v=AGrl-H87pRU)
- Blog : [Alexandre Stevens – Passionné Power BI](https://alexandrestevens.com)

---

## 📎 Auteur

Projet réalisé par **[Ton nom]** dans le cadre de la formation [Nom de ta formation ou école]  
Date : [Date du rendu]