# Ur III Acoustic Dataset

Ce dépôt contient les données acoustiques des rituels Ur III, publiées sur Zenodo.

📦 DOI : [10.5281/zenodo.9876543](https://doi.org/10.5281/zenodo.9876543)

---

## Description

Ce projet rassemble :

- Données brutes acoustiques (fichiers CSV)  
- Scripts d’analyse (Python)  
- Visualisations (images, graphiques)  
- Métadonnées complètes

---

## Licence

Ce projet est sous licence **Creative Commons Attribution - Non Commercial - Partage dans les Mêmes Conditions 4.0 International (CC BY-NC-SA 4.0)** pour les données, figures et documents.  
Les scripts et le code source sont sous licence **MIT** (voir les fichiers `LICENSE_DATA.txt` et `LICENSE_CODE.txt` pour plus de détails).

### Résumé des permissions :

- **Données et documents** : libre usage non commercial, avec attribution et partage sous la même licence.  
- **Code source** : usage, modification et redistribution libres, avec mention du copyright.

Pour les textes complets des licences, veuillez consulter :  
- CC BY-NC-SA 4.0 : https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode  
- MIT License : voir `LICENSE_CODE.txt`

---

## Installation et usage

```bash
git clone https://github.com/tonpseudo/UrIII_Acoustics.git
pip install -r requirements.txt  # si vous avez des dépendances
python scripts/analyse.py data/Venus_Cooccurrences.csv