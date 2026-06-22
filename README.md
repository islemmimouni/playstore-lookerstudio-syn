# 📊 Play Store → Looker Studio Sync

![Google Cloud](https://img.shields.io/badge/Google%20Cloud-Enabled-blue)
![BigQuery](https://img.shields.io/badge/BigQuery-Data%20Warehouse-orange)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-Dashboard-green)

---

## 📌 Description

Ce projet permet de synchroniser automatiquement les rapports de la **Google Play Console** vers **Looker Studio**, afin de créer des tableaux de bord analytiques avancés et suivre les performances des applications.

---

## 🛠️ Technologies utilisées

- Google Cloud Storage API
- Google BigQuery
- Looker Studio
- Google Play Console

---

## 📋 Prérequis

- Compte développeur Google Play
- Accès à Google Cloud Platform
- Bucket ID de la Play Console
- Autorisations BigQuery activées

---

## 📸 Captures d’écran

### 🔹 Dashboard principal

<p align="center">
  <img src="https://github.com/user-attachments/assets/fc8c61d5-cda4-441b-ab67-bf6ea2ce35f4" width="900">
</p>

---

### 🔹 Analyse des abonnements

<p align="center">
  <img src="https://github.com/user-attachments/assets/a6b31ff3-1506-4882-b040-775c8a26f452" width="900">
</p>

---

### 🔹 Configuration Cloud

<p align="center">
  <img src="https://github.com/user-attachments/assets/04f094ac-11f9-4ce3-85cc-c73ee9e6f1c9" width="900">
</p>

---

### 🔹 Export des données

<p align="center">
  <img src="https://github.com/user-attachments/assets/b4d9515e-3924-45a0-881f-1bf6fe740e82" width="900">
</p>

---

### 🔹 BigQuery Setup

<p align="center">
  <img src="https://github.com/user-attachments/assets/7a966c12-825f-4951-8515-07b0f5817280" width="900">
</p>

---

### 🔹 Looker Studio Dashboard

<p align="center">
  <img src="https://github.com/user-attachments/assets/4877423a-2783-42f1-bcaf-2ef48641b139" width="900">
</p>

---

### 🔹 Interface supplémentaire

<p align="center">
  <img src="https://github.com/user-attachments/assets/00e9cb80-ea28-44e0-a6ae-108323144d66" width="900">
</p>

---

## ⚙️ Architecture du projet

```text
Play Console
   ↓
Google Cloud Storage
   ↓
BigQuery Dataset
   ↓
Looker Studio Dashboard
