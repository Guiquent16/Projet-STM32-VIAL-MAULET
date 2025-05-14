# Projet STM32 VIAL MAULET - Système d'assurance - DRIVE SENTINEL

Ce projet utilise une carte **STM32 Nucleo L152RE** et le shield **X-Nucleo-IKS01A3**
---

##  Matériel utilisé

- STM32 Nucleo L152RE
- Capteur IKS01A3 & HTS221
- 8 LEDs pour indication de vitesse

---

##  Fonctionnalités

- Lecture de l'accélération sur l'axe X
- Calcul de la vitesse en m/s, cm/s et km/h
- Résultat en valeur absolue pour éviter les vitesses négatives
- Seuil LED : vitesse > 10 km/h

---

##  Exemple d'affichage UART

Infos moteur :
Temperature : 25.63 Degre Celsius | Humidite : 60.36 %HR

Resultats de votre conduite :

Acc 1 (mg): 13.00 | Acc 2 (mg): 1311.00
Vitesse estimee : 19.476 m/s | 1947.60 cm/s | 70.11 km/h

---

##  Compilation

- Outil : **STM32CubeIDE**
- Console UART
