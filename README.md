# SmartFIN Loan Mobile App - BPMN 2.0 Workflow

## 📌 Project Overview
Project ini mendokumentasikan alur kerja (business process) teknis dalam perbaikan flow mobile loan app.
Model ini dibuat menggunakan **Camunda Modeler** dengan standar **BPMN 2.0**.

## 🛠️ Key Logic & Features
Dalam diagram ini, saya mengintegrasikan beberapa elemen teknis tingkat lanjut:
* **Conditional Flows:** Validasi otomatis berdasarkan parameter (Kendaraan & Limit Pinjaman).
* **DMN (Decision Model and Notation):** Tabel keputusan untuk menentukan kelayakan nasabah.

## 🔍 QA & Analytical Perspective
Mengapa alur ini dirancang seperti ini?
1. **Risk Mitigation:** Setiap tahapan memiliki "gerbang" validasi untuk mencegah over credit plafond.
2. **Negative Testing:** Saya mensimulasikan skenario kegagalan (limit tidak mencukupi, usia kendaraan diatas batas maksimum).
3. **Data Integrity:** Memastikan sinkronisasi data dari BE ke FE.

## 📂 Files in this Repo
* `/diagrams`: File mentah `.bpmn` (Bisa dibuka di Camunda).
* `/exports`: Hasil ekspor format `.svg` dan `.png` kualitas tinggi.
* `/docs`: Penjelasan detail mengenai skenario testing.

---
*Created by ATitanni - Senior QA Engineer & Aspiring Business Analyst*
