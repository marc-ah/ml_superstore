# ml_superstore
ADS-04 Studienarbeit Superstore Datensatz

In diesem Projekt wird versucht, mit  Hilfe von Machine Learning Algorithmen anhand verschiedener Bestelldaten Lieferverzögerungen in einem fiktiven Onlineshop vorherzusagen.
Für nähere inhaltliche Erläuterungen lesen Sie die Datei DSBA_ADS-04_Seminararbeit_Marc_Hofmann.pdf

# Verwendete Technologien
Jupyter Notebooks mit Python 3

Verwendete Module:
* pandas
* numpy
* sqlite3 
* os
* pandas_profiling
* seaborn
* hashlib
* sklearn
* pickle
* six
* IPython
* pydot
* time
* random
* winsound

# Übersicht der Dateien und Ordner

- Root
-- data
--- superstore.db         SQLite-Datenbank: Bereinigte und anonymisierte Daten 
-- input
--- global-superstore.xls Rohaten/Datenquelle
-- output                 Ordner für Ausgaben, z.B. Profile
-- scripts          
--- 01_import.ipynb       Notebook für Import der Exceldatei, Bereinigung und Anonymisierung
--- 02_inspect.ipynb      Deskritive Analyse des Datensatzes, Vorbereitung der Daten
--- 03_feature_eng.ipynb  Feature Engineerung und Modellerzeugung, Testing
-- temp                   Temporäres Verzeichnis für Übertragung von Notebook zu Notebook mittels Pickle
-- README.md             Diese Datei
