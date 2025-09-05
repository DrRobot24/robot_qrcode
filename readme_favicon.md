# 🤖 Robot-Code QR Generator

<div align="center">

![Robot-Code](https://img.shields.io/badge/Robot--Code-QR%20Generator-blueviolet?style=for-the-badge&logo=qrcode)
![Version](https://img.shields.io/badge/version-1.0.0-success?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![Made with Love](https://img.shields.io/badge/made%20with-❤️%20%26%20☕-red?style=for-the-badge)

**Un generatore QR code avanzato, personalizzabile e completamente offline**

[🚀 **Prova il Generatore**](https://robot-code-qr.vercel.app) • [📖 **Documentazione**](#-features) • [🐛 **Segnala Bug**](https://github.com/tuousername/robot-code-qr/issues)

![QR Generator Demo](https://via.placeholder.com/600x400/667eea/ffffff?text=Demo+Screenshot)
*↑ Inserisci qui uno screenshot del tuo generatore*

</div>

---

## 🎯 **Cos'è Robot-Code?**

Robot-Code è un generatore QR avanzato che ti permette di creare codici QR personalizzati con:
- 🎨 **Colori custom** - Abbina il QR al tuo brand
- 🎭 **Stili predefiniti** - Ocean, Sunset, Neon e altri
- 👀 **Anteprima live** - Vedi i cambiamenti istantaneamente  
- 🛡️ **Privacy totale** - Tutto funziona offline nel browser
- 📱 **Responsive design** - Perfetto su desktop e mobile

> **Filosofia**: Nessun server esterno, nessun tracking, nessun limite. Il tuo QR generator personale!

---

## ✨ **Features**

### 🎨 **Personalizzazione Avanzata**
- **Color picker completi** per foreground e background
- **6 stili predefiniti** professionali (Oceano, Tramonto, Foresta, Neon, Retro, Classico)  
- **Dimensioni variabili** da 128px a 512px
- **4 livelli di correzione errori** (L, M, Q, H)

### 🚀 **User Experience**
- **Anteprima in tempo reale** dei colori scelti
- **Generazione istantanea** - zero tempi di attesa
- **Download diretto** in PNG alta qualità
- **Scorciatoia Ctrl+Enter** per power users

### 🔒 **Privacy & Performance**
- **100% offline** - nessun dato inviato a server esterni
- **Zero dependencies** esterne (solo QRious.js via CDN)
- **Lightweight** - carica in <2 secondi
- **Cross-browser** - funziona ovunque

---

## 🎯 **Casi d'uso**

| Tipo QR | Esempio | Livello Errori Consigliato |
|---------|---------|----------------------------|
| 🌐 **Website** | `https://tuosito.com` | M - Media |
| 📧 **Email** | `mailto:info@email.com` | M - Media |  
| 📱 **Telefono** | `tel:+393201234567` | L - Bassa |
| 📶 **WiFi** | `WIFI:T:WPA;S:NomeRete;P:Password;;` | H - Alta |
| 💼 **vCard** | Biglietto da visita digitale | Q - Alta |
| 📱 **SMS** | `sms:+393201234567:Ciao!` | M - Media |

---

## 🛠️ **Tech Stack**

| Tecnologia | Versione | Utilizzo |
|------------|----------|----------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | HTML5 | Struttura e semantica |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | CSS3 | Styling e animazioni |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Vanilla ES6+ | Logica applicativa |
| ![QRious](https://img.shields.io/badge/QRious-4.0.2-success) | 4.0.2 | Generazione QR code |

### 🏗️ **Architettura**
```
📁 robot-code-qr/
├── 📄 index.html          # Single Page Application completa
├── 📄 README.md           # Questa documentazione  
├── 📄 LICENSE             # Licenza MIT
└── 🎨 favicon.ico         # Icona robot personalizzata
```

---

## 🚀 **Quick Start**

### 1️⃣ **Usa subito** (Raccomandato)
```bash
# Apri nel browser
https://robot-code-qr.vercel.app
```

### 2️⃣ **Clona localmente**
```bash
# Clone del repository
git clone https://github.com/tuousername/robot-code-qr.git

# Apri il file
cd robot-code-qr
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### 3️⃣ **Deploy la tua versione**
```bash
# Fork il progetto su GitHub
# Connetti a Vercel/Netlify  
# Deploy automatico in 30 secondi! 🚀
```

---

## 🎮 **Come usare**

1. **📝 Inserisci contenuto** - URL, testo, email, telefono...
2. **🎨 Personalizza stile** - Scegli colori o usa preset
3. **⚙️ Configura opzioni** - Dimensione e correzione errori  
4. **✨ Genera QR** - Click o Ctrl+Enter
5. **💾 Scarica** - PNG pronto per l'uso!

### 🔥 **Pro Tips**
- **Contrasto alto**: Usa colori molto diversi per massima leggibilità
- **Test sempre**: Prova a scansionare con il tuo telefono
- **Dimensioni grandi**: Per stampe, usa almeno 300px
- **Livello H**: Se vuoi aggiungere un logo centrale

---

## 🌟 **Roadmap Future**

- [ ] 🎨 **Forme personalizzate** (dots rotondi, quadrati smussati)
- [ ] 🖼️ **Logo centrale** con upload immagine
- [ ] 📊 **Batch generation** per più QR contemporaneamente  
- [ ] 💾 **Cronologia** dei QR generati (localStorage)
- [ ] 🌍 **PWA** installabile come app mobile
- [ ] 🎯 **QR Analytics** con tracking visite (opzionale)
- [ ] 📱 **Deep linking** per app mobile

---

## 🤝 **Contribuire**

Contributi, issues e feature requests sono benvenuti! 

1. **🍴 Fork** il progetto
2. **🌿 Crea** il tuo feature branch (`git checkout -b feature/AmazingFeature`)
3. **💾 Commit** le modifiche (`git commit -m 'Add some AmazingFeature'`)
4. **📤 Push** al branch (`git push origin feature/AmazingFeature`)
5. **🔄 Apri** una Pull Request

### 🐛 **Bug Reports**
Usa il [template issue](https://github.com/tuousername/robot-code-qr/issues/new) per segnalare bug.

---

## 👨‍💻 **Autore**

**Il Tuo Nome**
- 🌐 Website: [tuosito.com](https://tuosito.com)
- 📧 Email: tua@email.com  
- 💼 LinkedIn: [@tuoprofile](https://linkedin.com/in/tuoprofile)
- 🐦 Twitter: [@tuousername](https://twitter.com/tuousername)

---

## 📄 **Licenza**

Questo progetto è sotto licenza MIT - vedi [LICENSE](LICENSE) per i dettagli.

```
MIT License - Sei libero di:
✅ Usare commercialmente
✅ Modificare il codice  
✅ Distribuire
✅ Uso privato
```

---

## 🙏 **Ringraziamenti**

- [**QRious.js**](https://github.com/neocotic/qrious) - Libreria QR code eccezionale
- [**Vercel**](https://vercel.com) - Hosting e deploy gratuito
- [**GitHub**](https://github.com) - Code hosting e versioning
- [**Shields.io**](https://shields.io) - Badge fighi per il README

---

## 📊 **Stats**

![GitHub stars](https://img.shields.io/github/stars/tuousername/robot-code-qr?style=social)
![GitHub forks](https://img.shields.io/github/forks/tuousername/robot-code-qr?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/tuousername/robot-code-qr?style=social)

---

<div align="center">

**⭐ Se questo progetto ti è utile, lascia una stella! ⭐**

**🤖 Made with code, coffee and lots of learning 🤖**

[⬆ Torna su](#-robot-code-qr-generator)

</div>