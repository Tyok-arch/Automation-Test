# QA Automation Template (Cypress & AI Agent Workflow)

Template otomasi pengujian End-to-End (E2E) menggunakan **Cypress** yang sudah terintegrasi dengan **GitHub Actions CI/CD Pipeline**.

## 🛠️ Alur Kerja (Workflow)
1. Analisis PRD / Spesifikasi UI oleh AI Agent.
2. Generasi skenario pengujian (Positif & Negatif) dan skrip Cypress (`.cy.js`).
3. Eksekusi lokal via Cypress Runner.
4. Integrasi otomatis di Cloud via GitHub Actions saat `git push`.

## 🚀 Cara Penggunaan Lokal

1. **Install Dependencies:**
   ```bash
   npm install
