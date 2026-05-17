## Despre proiect

Acest proiect reprezintă un set de wireframe-uri pentru interfețe automotive.

---

## Componente realizate

### 1. Ecran central Infotainment
**Rezoluție:** 1280 × 800 px

Ecranul principal al mașinii, împărțit în 3 zone funcționale:

- **Navigație (stânga)** — hartă, destinație curentă, și indicator de viraj activ
- **Media (centru)** — player muzică cu artwork, titlu, artist, progress bar și controale
- **Climatizare (dreapta)** — temperatură față/spate cu controale individuale, trepte ventilator și buton A/C

---

### 2. Digital Instrument Cluster
**Rezoluție:** 1920 × 720 px

Clusterul de bord digital cu 3 indicatoare principale:

- **RPM (stânga)** — turație motor cu temperatură motor
- **Viteză (centru)** — vitezometru principal cu indicator limită de viteză
- **Combustibil (dreapta)** — nivel combustibil procentual

**Elemente ADAS:** Indicator Lane Assist pentru asistența la menținerea benzii — plasat central, sub vitezometru, vizibil fără să distragă.

---

### 3. Head-Up Display (HUD)
**Rezoluție:** 1200 × 500 px

Proiecție simulată pe parbriz cu informații esențiale pentru condus:

- **Viteză curentă** — element principal, cyan (#00E5FF) pentru vizibilitate pe orice fundal
- **Indicator navigație** — săgeată direcție + distanță până la viraj
- **Limită viteză** — indicator circular roșu/alb, standard internațional
- **ADAS status** — Lane Assist și urmărire distanță

---

## Principii UX aplicate

| Principiu | Aplicare în proiect |
|-----------|-------------------|
| **Glance time < 2s** | Informațiile critice (viteză, navigație) sunt mari și centrate |
| **Ierarhia informației** | Datele esențiale sunt mereu vizibile, setările sunt secundare |
| **Consistency** | Același status bar, aceleași culori și convenții pe toate cele 3 ecrane |
| **Error prevention** | Indicatorul de limită de viteză lângă vitezometru — comparație imediată |
| **Aesthetic & minimal** | Dark theme, fără elemente decorative, doar informație funcțională |

---

## Tool-uri folosite

- **Figma** — wireframing și layout