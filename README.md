# v-lice-clustering

Dieses Repository enthält den Code zur diachronen semantischen Analyse der russischen komplexen Präposition **в лице** mithilfe von kontextualisierten Wortvektoren (BERT) und Clustering-Verfahren.

## Inhalt

- `v_lice_clustering.py`: Hauptskript zur Vektorberechnung und Clusteranalyse mit RuBERT.
- `requirements.txt`: Verwendete Python-Bibliotheken.
- `README.md`: Diese Datei.

## Installation

```bash
pip install -r requirements.txt
```

## Ausführung

Das Skript nutzt den `DeepPavlov/rubert-base-cased`-Tokenizer und das Modell von HuggingFace. Die Daten werden aus einer Google-Sheet-Tabelle geladen, BERT-Vektoren erzeugt und k-means-Clustering durchgeführt.

## Voraussetzungen

- Python 3.7+
- HuggingFace Transformers
- torch
- scikit-learn
- pandas
- numpy
- pygsheets

## Lizenz

MIT License