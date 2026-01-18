           #Gabès Pollution Impact Simulation
<div align="center">
  Gabès Through the Lens of Simulation
Simuler l'Impact | Sauver des Vies | Protéger Gabès
"Il était une fois, Gabès était un joyau méditerranéen..."

Ce projet n'est pas qu'une simple simulation statistique. C'est un témoignage numérique qui quantifie la douleur silencieuse d'une communauté, la perte invisible d'années de vie, et le prix humain du "développement" industriel.
</div>
🎯 Objectives
Quantify potential life years lost due to industrial PM2.5 exposure

Visualize the invisible health burden on Gabès residents

Advocate for evidence-based environmental policies

Educate about the human cost of industrial pollution

**Concepts Clés Définis**
Définition :

Particules fines d'un diamètre inférieur à 2.5 micromètres (30 fois plus fines qu'un cheveu humain).

**Pourquoi c'est dangereux ?**
 Pénétration profonde : Atteignent les alvéoles pulmonaires
 
 Voyage sanguin : Passent dans le système circulatoire
 
Effet cumulatif : S'accumulent dans l'organisme sur des années

 Cible multiple : Cœur, poumons, cerveau, système reproductif

**À Gabès : Principalement émises par l'industrie chimique du phosphate!!!!!**

Methodology & Data Sources
Core Mathematical Model
python
LE_adj = LE_ref / exp(β × ΔPM2.5)
Where:

LE_adj = Adjusted life expectancy (years)

LE_ref = 77.0 years (Tunisia 2023, INS)

β = 0.0077 (WHO risk coefficient)

ΔPM2.5 = PM2.5 increase (μg/m³)

exp() = Exponential function

Reference: *WHO (2021). Global Air Quality Guidelines. RR=1.08 per 10μg/m³.*
## 📊 Data Sources & References

| Data Type | Value | Source | Year | Confidence |
|:----------|:------|:-------|:-----|:----------|
| **Life Expectancy** | 77.0 years | INS Tunisia - National Statistics Institute | 2023 | 🟢 High |
| **PM2.5 Risk Coefficient** | 1.08 per 10μg/m³ | WHO Global Air Quality Guidelines | 2021 | 🟢 High |
| **Simulated Health Impact** | 15.7 years lost | This simulation (30μg/m³ scenario) | 2026 | 🟡 Medium |
| **Regional Context** | Industrial pollution patterns | Ben Brahim et al., *J. Environ. Manage.* | 2019 | 🟢 High |
| **Population Data** | ~150,000 residents | Gabès Governorate Census | 2023 | 🟢 High |
| **Validation Data** | Respiratory disease rates | Tunisian Ministry of Health | 2022 | 🟡 Medium |

## 🔬 Simulation Scenarios

| Scenario | ΔPM2.5 | Life Expectancy | Years Lost | Health Impact |
|:---------|:-------|:----------------|:-----------|:--------------|
| **🌿 Baseline** | 0 μg/m³ | 77.0 years | 0.0 years | ✅ No impact |
| **🌤️ Low** | 5 μg/m³ | 74.1 years | 2.9 years | ⚠️ Moderate |
| **🌫️ Medium** | 15 μg/m³ | 68.7 years | 8.3 years | 🚨 Significant |
| **☠️ high dangerous Case** | **30 μg/m³** | **61.3 years** | **15.7 years** | **🔥 Critical** | 

Vie Complète (77 ans)   : ████████████████████████████████████████████████████████████
Scénario Léger (5)      : ████████████████████████████████████████████████████████░░░░ (-2.9 ans)
Scénario Moyen (15)     : █████████████████████████████████████████████████░░░░░░░░░░░ (-8.3 ans)
Scénario critique  (30)     : ████████████████████████████████████████████░░░░░░░░░░░░░░░░ (-15.7 ans)


**ATTENTION : Clarification Importante**
Note Méthodologique : Les valeurs de PM2.5 utilisées ici (0, 5, 15, 30 µg/m³) sont des scénarios hypothétiques basés sur :

La tendance actuelle d'augmentation de la pollution

Les niveaux observés dans d'autres zones industrielles similaires

Une projection de ce qui pourrait arriver si aucune mesure n'est prise

Nous ne disposons pas de mesures continues officielles des PM2.5 à Gabès.
Cette simulation montre l'impact potentiel si la pollution atteignait ces niveaux.


**📚 Academic Context**
Primary References:
WHO (2021) - Global Air Quality Guidelines

INS Tunisia (2023) - Demographic Statistics

Ben Brahim et al. (2019) - Gabès Environmental Impact

Burnett et al. (2018) - Global PM2.5 Mortality

🎓 Authors & Institution
Lead Researcher:
Hiba MAHROUG
ISIMM, University of Monastir
zarouihiba@gmail.com

Supervisor:
Prof. Nada HAJ MESSAOUD
Department of Computer Science, ISIMM

Academic Year: 2025/2026
Project Type: Mini-Project / Research Simulation
<div align="center">
