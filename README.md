# Klasifikacija simptoma bolesti lista paprike

Ovaj projekat predstavlja implementaciju sistema za automatsku
klasifikaciju simptoma bolesti lista paprike na osnovu slika,
koristeci tehnike obrade slike i masinskog ucenja.

## Dataset
Koriscen je javno dostupan Kaggle Chili Plant Disease Dataset.

Razmatrane klase:
- healthy (zdravo lisce)
- whitefly (simptomi pepelnice)
- yellowish (simptomi plamenjace)

## Metodologija
- Poboljsanje kontrasta: CLAHE
- Segmentacija slike: K-means algoritam
- Morfoloske operacije za ciscenje maske
- Ekstrakcija karakteristika
- Klasifikacija: Support Vector Machine (SVM)

## Rezultati
- Ukupna tacnost klasifikacije: 83.3%
- Evaluacija izvrsena pomocu:
  - accuracy
  - precision, recall i F1 mjere
  - matrice konfuzije

## Pokretanje koda

Kod je razvijen i testiran u Google Colab okruzenju.

1. Otvoriti notebook `Bolesti_Lisca.ipynb` u Google Colab-u.
2. Podesiti putanje do dataseta (train, val, test).
3. Pokrenuti sve celije redom.
