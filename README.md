# Hälsostudie – Python och statistik

## Beskrivning
Detta projekt är en individuell uppgift i kursen Python och statistik.

Syftet är att analysera data från en hälsostudie med hjälp av Python och statistiska metoder.

## Del 1 – Grundläggande analys och statistik

Analysen innehåller:

- Beskrivande statistik: medelvärde, median, min och max.
- Visualisering med histogram, lådagram och stapeldiagram.
- Simulering av sjukdomsförekomst med NumPy.
- Beräkning av 95 % konfidensintervall för systoliskt blodtryck.
- Hypotesprövning av blodtryck hos rökare och icke-rökare.
- Resultat och tolkningar i Jupyter Notebook.

## Projektstruktur

- `data/health_study_dataset.csv` – dataset
- `notebooks/health_study.ipynb` – analys och resultat
- `requirements.txt` – Python-bibliotek
- `README.md` – projektbeskrivning

## Verktyg och bibliotek

- Python 3.14
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- SciPy

## Så körs projektet

1. Installera biblioteken med `pip install -r requirements.txt`.
2. Öppna `notebooks/health_study.ipynb` i VS Code med Jupyter.
3. Kör alla celler i ordning med **Restart & Run All**.

## Reproducerbarhet

Projektet använder relativa sökvägar till datasetet och `np.random.seed(42)` för att simuleringarna ska kunna upprepas.