##  Description de la table CONTRATS

La table **CONTRATS** contient les informations contractuelles, techniques et socio-démographiques
relatives à un portefeuille d’environ **824 000 lignes** (avenants).

Chaque ligne correspond à une période de couverture d’un véhicule assuré.

La base regroupe plusieurs types d’informations :

---

### 🆔 1. Identification du contrat et du risque
- **NSOC** : Numéro de sociétaire  
- **NRIS** : Numéro de risque / véhicule  
- **NREPVEH** : Numéro de répertoire du véhicule  

---

### 📅 2. Informations temporelles
- **DEBUT** : Date de début d’avenant  
- **FIN** : Date de fin d’avenant  
- **DNAICDD** : Date de naissance du conducteur  
- **DPERCDD** : Date d’obtention du permis  
- **DFINFABMOD** : Date de fin de fabrication du modèle  

---

### 🚗 3. Caractéristiques du véhicule
- **ANCVEH** : Ancienneté du véhicule (en années)  
- **CCATVEH** : Code catégorie véhicule  
- **CGENVEH** : Code genre véhicule  
- **CSEGVEH** : Code segment  
- **CENEVEH** : Code énergie  
- **CVOCVEH** : Code vocation  
- **CNFIVEH** : Code finition  
- **CSRAVEH** : Code modèle SRA  
- **CGROSRA** : Code groupe SRA  
- **CSRA** : Cotation SRA  
- **CCLAREP** : Classe réparation  
- **CCLAPRX** : Classe prix  
- **CSTYPVEH** : Code sous-type véhicule  
- **LMAR** : Marque du véhicule  
- **QVITVEH** : Vitesse maximale  
- **QPUIFIS** : Puissance fiscale  
- **QPORVEH** : Nombre de portes  
- **MVALVEH** : Valeur à neuf du véhicule  

---

### 📑 4. Garanties et options contractuelles
- **CFORASU** : Formule d’assurance  
- **CNIVASP** : Option assistance  
- **CNIVFRN** : Niveau de franchise  
- **CNIVOTR** : Option biens transportés  
- **CNIVSVR** : Option véhicule de remplacement  

---

### 📊 5. Profil de risque et historique
- **CSINANN** : Sinistralité antérieure  
- **CPEVANN** : Période sans événement  
- **KCLAANN** : Coefficient Bonus-Malus (CRM)  
- **QECH050** : Nombre d’échéances avec CRM à 0,50  
- **CTBR** : Code très bon risque (CRM = 0,50 pendant 4 ans)  
- **CUSARIS** : Usage du véhicule  

---

### 👤 6. Caractéristiques du conducteur et socio-démographie
- **CPER** : Type de personne  
- **TCDD** : Statut du conducteur  
- **csexe** : Sexe  
- **cpos** : Code postal de résidence  
- **cemp** : Code employeur  
- **cdomact** : Domaine d’activité  
- **cprosoc** : Profession  
- **sfam** : Situation familiale  
- **qenf** : Nombre d’enfants à charge  

