# 🛑 Traffic Sign Recognition using CNN

Ein Deep Learning Projekt zur Erkennung und Klassifikation von Verkehrszeichen, trainiert auf dem **GTSRB (German Traffic Sign Recognition Benchmark)** Datensatz.

Dieses Projekt wurde im Rahmen meines Wirtschaftsinformatik-Studiums (Schwerpunkt Data Science & KI) entwickelt.

## 📋 Projektübersicht

Das Ziel war die Entwicklung eines **Convolutional Neural Network (CNN)**, das Bilder von 43 verschiedenen Verkehrszeichenklassen korrekt klassifiziert.

* **Training:** `ProjektKIAbgabe.ipynb` – Datenaufbereitung, Modellarchitektur, Training und Evaluierung.
* **Anwendung:** `anwendung.ipynb` – Lädt das trainierte Modell und erlaubt Vorhersagen auf neuen Bildern.

## 🛠️ Tech Stack

* **Sprache:** Python 3.9
* **Frameworks:** TensorFlow / Keras
* **Data Science:** Pandas, NumPy, Scikit-Learn
* **Visualisierung:** Matplotlib, Seaborn

## 📊 Ergebnisse

Das Modell erreicht eine hohe Genauigkeit auf den Testdaten.
* **Architektur:** Custom CNN (Conv2D, MaxPool, Dropout, Dense Layers)
* **Input:** 30x30 Pixel RGB Bilder
* **Klassen:** 43

## 🚀 Installation & Nutzung


### 1. Umgebung einrichten
```bash

# Repository klonen
git clone [https://github.com/DEIN_USERNAME/DEIN_REPO_NAME.git](https://github.com/DEIN_USERNAME/DEIN_REPO_NAME.git)

# Abhängigkeiten installieren
pip install pandas numpy pillow matplotlib scikit-learn seaborn tensorflow jupyter
```

### 2. Daten beschaffen

    Lade den GTSRB - German Traffic Sign Recognition Benchmark Datensatz herunter (z.B. von Kaggle).

    Entpacke die Daten so, dass der Ordner Train (mit den Unterordnern 0-42) im Hauptverzeichnis liegt.

### 3. Modell trainieren

Starte das Jupyter Notebook ProjektKIAbgabe.ipynb und führe alle Zellen aus. Dies generiert die Modelldatei traffic_sign_cnn_model.keras.

### 4. Demo testen

Öffne anwendung.ipynb, um das trainierte Modell zu testen. Du kannst eigene Bilder oder Bilder aus dem Test-Set verwenden, um die Erkennung zu prüfen.
📂 Dateistruktur

    ProjektKIAbgabe.ipynb: Haupt-Notebook für Training & Analyse.

    anwendung.ipynb: Interaktives Notebook zur Nutzung des Modells.

    classes_readable.csv: Mapping der Class-IDs (0-42) zu lesbaren Namen.

    traffic_sign_cnn_model.keras: Das trainierte Modell (wird durch Training generiert).