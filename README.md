# Titanic - Machine Learning Project

## Opis projektu

Projekt polega na analizie danych pasażerów statku Titanic oraz budowie modeli uczenia maszynowego przewidujących przeżycie pasażera (klasyfikacja binarna).

Projekt został wykonany w ramach przedmiotów:
- Elementy Data Mining  
- Wprowadzenie do Uczenia Maszynowego  
- Uczenie Maszynowe w Praktyce  

---

## Zbiór danych

Dane pochodzą z Kaggle:
https://www.kaggle.com/datasets/yasserh/titanic-dataset

Zawierają informacje o pasażerach Titanic, takie jak:
- płeć
- wiek
- klasa biletu
- opłata
- port zaokrętowania

---

## Cel projektu

Celem projektu jest zbudowanie modelu klasyfikacyjnego, który przewiduje:
- czy pasażer przeżył katastrofę (1)
- czy nie przeżył (0)

---

## Metody

W projekcie zastosowano:

- analiza eksploracyjna danych (EDA)
- preprocessing danych
- pipeline w scikit-learn
- regresja logistyczna
- Random Forest
- walidacja krzyżowa (cross-validation)
- optymalizacja hiperparametrów (GridSearchCV)

---

## Modele

### Logistic Regression
- Accuracy test: ~0.804
- CV accuracy: ~0.786

### Random Forest
- Accuracy test: ~0.804
- CV accuracy: ~0.814

---

## Wnioski

- oba modele osiągnęły podobną skuteczność (~80%)
- Random Forest lepiej radzi sobie w walidacji krzyżowej
- regresja logistyczna jest bardziej interpretowalna
- dane mają umiarkowaną złożoność

---

## Technologie

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

