## Données d’entrée (sources brutes)
- [crimes-et-delits-enregistres-par-les-services-de-gendarmerie-et-de-police-depuis-2012.xlsx](crimes-et-delits-enregistres-par-les-services-de-gendarmerie-et-de-police-depuis-2012.xlsx)
- [DS_ESTIMATION_POPULATION_data.csv](DS_ESTIMATION_POPULATION_data.csv)
- [DS_ESTIMATION_POPULATION_metadata.csv](DS_ESTIMATION_POPULATION_metadata.csv)

## Pipeline ETL (préparation des données)
- [merge_and_clean_crimes.py](merge_and_clean_crimes.py)
- [process_population.py](process_population.py)

## Migration / Base de données (schéma + chargement)
- [schema_crimes.sql](schema_crimes.sql)
- [create_and_load_db.py](create_and_load_db.py)

## Données de sortie (données transformées)
- [crimes_clean_2012_2021.csv](crimes_clean_2012_2021.csv)
- [population_by_dept_year.csv](population_by_dept_year.csv)

## Base de données générée
- [crimes_database.db](crimes_database.db)

## Rapport & modélisation
- [MCD.md](MCD.md)
- [MLD.md](MLD.md)
- [Modèle_graph.png](Mode%CC%80le_graph.png)
- [exemple_requete.png](exemple_requete.png)
- [Rapport final.md](Rapport%20final.md)
