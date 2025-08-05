<div align="center">
  
  ![Banner](https://raw.githubusercontent.com/Milanhe92/milanhe92/main/assets/banner.png)
  
  ### 🚀 Inovator na raskrsnici kvantnog računarstva, blockchaina i veštačke inteligencije
  
  [![Visitors](https://komarev.com/ghpvc/?username=milanhe92&label=PROFIL+POGLEDA&color=blueviolet)](https://github.com/Milanhe92)
  [![Repositories](https://badgen.net/badge/REPO/80/purple)](https://github.com/Milanhe92?tab=repositories)
  [![TON Expert](https://img.shields.io/badge/TON-Developer-yellow)](https://ton.org)
  
</div>

---

### 🔥 Aktuelni projekti
| Projekt | Tehnologije | Status |
|---------|-------------|--------|
| [Melektron AI](https://github.com/Milanhe92/Melektron-ai) | Next.js, TON, Quantum | 🚀 Produkcija |
| [TON Blockchain Tools](https://github.com/Milanhe92/ton-utils) | Solidity, TON SDK | ⚡ Aktivan razvoj |
| [Quantum Core](https://github.com/Milanhe92/quantum-core) | Python, Qiskit | 🔬 Istraživanje |

---

### 🛠 Tehnološki stack
```mermaid
graph LR
  A[Blockchain] --> B[TON]
  A --> C[Solidity]
  D[AI] --> E[TensorFlow]
  D --> F[PyTorch]
  G[Web] --> H[Next.js]
  G --> I[React]
  J[Kvantno] --> K[Qiskit]
  J --> L[Cirq]

### Dodatni elementi za GitHub profil:  
1. **Dinamički banner**:  
   - Kreirajte `assets/banner.png` u repozitorijumu  
   - Preporuka: Canva ili Figma sa temom kvantnog računarstva  
---
2. **Prikvačeni repozitorijumi**:  
   - Idite na profil → "Customize your pins"  
   - Odaberite 6 najvažnijih projekata  
   - Preporuka:  
     - Melektron-ai  
     - Melektron-v9  
     - sdk  
     - quantum-core  
     - ton-utils  
     - execution-apis  

3. **Achievements**:  
   - U "Achievements" sekciji aktivirajte:  
     - Pair Extraordinaire  
     - Quickdraw  
     - Starstruck  

4. **GitHub Actions za automatsko ažuriranje**:  
   Dodajte `.github/workflows/update-readme.yml`:  
   ```yaml
   name: Update Profile
   on:
     schedule:
       - cron: '0 0 * * *'
     workflow_dispatch:
   jobs:
     update:
       runs-on: ubuntu-latest
       steps:
         - uses: actions/checkout@v4
         - name: Update stats
           uses: AnandChowdhary/activity-box@latest
           with:
             GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
         - name: Commit changes
           run: |
             git config user.name github-actions
             git config user.email actions@users.noreply.github.com
             git add .
             git commit -m "Update stats"
             git push
