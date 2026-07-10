# Grace Samira Ngouana : Portfolio Data Analyst

Étudiante en **Master 2 Data Analyst (MASERATI, UPEC)**  en recherche d'alternance pour septembre 2026 (3 jours entreprise / 2 jours université).

Spécialisée en **modélisation statistique, scoring de risque et visualisation de données**. Formation d'économiste appliquée : j'aime les résultats qui se défendent, pas seulement les modèles qui tournent.

📫 ngouanasamira79@gmail.com · [LinkedIn](https://linkedin.com/in/ngouana-grace) · Île-de-France

---

## 🗂 Projets

### 1. [Scoring crédit - Modélisation du risque de défaut](./scoring-credit)

Prédiction de la probabilité de défaut sur **150 000 emprunteurs** (dataset Give Me Some Credit).

| Modèle | AUC | Gini | KS |
|---|---|---|---|
| Régression logistique | 0,814 | 0,627 | 0,495 |
| Random Forest | **0,854** | **0,708** | **0,552** |

Gestion du déséquilibre de classes (6,68 % de défauts), validation stratifiée, **explicabilité via SHAP values** — les principaux facteurs de risque identifiés sont le taux d'utilisation du crédit renouvelable et les retards de paiement passés.

**Stack :** Python · Pandas · Scikit-learn · SHAP · Matplotlib

### 2. [Dashboard Power BI - Performance commerciale](./dashboard-performance-commerciale)

Rapport interactif de 3 pages sur **9 994 transactions retail** : modèle en étoile (4 tables), 6 mesures DAX, slicers dynamiques région/segment/catégorie.

Résultats clés : écart de marge de **14,94 % (West) à 7,92 % (Central)**, sous-catégories à profit négatif identifiées (Tables, Bookcases) — restitution orientée aide à la décision.

**Stack :** Power BI, DAX, Power Query

### 3. Mémoire de Master - Disparités régionales des inégalités salariales F/H en France

Analyse microéconométrique sur l'**Enquête Emploi en Continu INSEE 2023-2024 (N = 46 494)** : OLS, effets fixes, correction du biais de sélection (Heckman deux étapes), décomposition Oaxaca-Blinder.

Résultat principal : pénalité salariale féminine de **−11,4 % (OLS), portée à −15,2 % après correction du biais de sélection**, avec une variation territoriale statistiquement validée. La pénalité salariale existe et diffère selon le type de territoire

*Les données Progedo sont sous convention d'accès et ne peuvent pas être partagées ici.*

**Stack :** R ,fixest, oaxaca, ggplot2, sf

---

## 🛠 Compétences

**Langages :** Python, R, SQL, SAS · **ML :** scikit-learn, SHAP, validation croisée · **BI :** Power BI (DAX, modélisation en étoile), Excel avancé · **Économétrie :** Heckman, Oaxaca-Blinder, effets fixes, tests de robustesse
