# ![Ortho Planning Tools](https://surgicalscripts.github.io/ortho-planning-tools/) <-- klikni na odkaz pro otevření stánky s měřením

**Profesionální webová aplikace pro plánování ortopedických operací na RTG snímcích dolních končetin.**

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Offline](https://img.shields.io/badge/offline-100%25-orange)

---

## 📖 Rychlý start

### 1. Nahrání snímku
- Klikni **"📁 Nahrát RTG"**
- Vyber JPG nebo PNG soubor
- Snímek se zobrazí na canvas

### 2. Plánování osteotomie
- Klikni **"🔪 Osteotomie"**
- Označ **5 bodů**:
  1. Začátek řezu
  2. Konec řezu (= střed rotace, hinge)
  3. Pravý kotník
  4. Pata
  5. Levý kotník
- Použij **slider** pro rotaci
- Klikni **"👁️ Před op."** pro zobrazení klínu
- **Export JPG** - exportuje preview NEBO pooperační stav

### 3. Měření úhlů
- Klikni **"∠ Měřit úhel"**
- První kliknutí → Vyber počet měření
- Další kliknutí → Rychle přidává jednotlivá měření
- Označ **3 body**: začátek ramene → vrchol → konec ramene
- Úhel se automaticky vypočítá
- **🗑️** - smaž konkrétní měření

### 4. Měření vzdáleností
- Klikni **"📏 Kalibrace"**
- Označ 2 body na známé vzdálenosti (např. pravítko)
- Zadej skutečnou vzdálenost v cm
- Klikni **"📏 Měřit vzdálenost"**
- Označ 2 body které chceš změřit
- Vzdálenost se zobrazí v cm

---

## 🎨 Ovládání

### Myš
- **Kolečko** - Zoom in/out
- **Pravé tlačítko + tažení** - Posun snímku
- **Ctrl + levé tlačítko + tažení** - Posun snímku
- **Levé tlačítko na bod** - Přesun bodu (u měření)

### Tlačítka
- **🔄 Reset zobrazení** - Vrátí zoom a posun na výchozí
- **💾 Export JPG** - Uloží snímek se všemi značeními

---

## 🎯 Hlavní funkce

### 🔪 Plánování osteotomií
- 5-bodový systém pro precizní označení řezu
- Automatická detekce **OPEN** / **CLOSE wedge** podle směru rotace
- Slider pro rotaci (-30° až +30°)
- **Preview režim "Před/Po operaci"**
  - Před operací: Červený klín ukazuje část kosti k odstranění + hodnota úhlu
  - Po operaci: Rotovaná kost s vizualizací výsledku
- Export obou stavů do JPG

### 📐 Měření úhlů
- Automatické ramena pro přesné měření
- Neomezený počet měření
- Switch úhlu (reflex/non-reflex)
- Skrytí/zobrazení jednotlivých měření
- Individuální mazání (🗑️ u každého měření)

### 📏 Měření vzdáleností
- Kalibrace pomocí známé vzdálenosti
- Automatický přepočet pixel → cm
- Neomezený počet měření
- Individuální mazání

### 🦴 Knihovna dlah
- 3 vestavěné dlahy (T, L, straight plate)
- Možnost nahrát vlastní dlahy (PNG)
- Rotace, změna velikosti, přesun
- Průhlednost (viditelnost kosti pod dlahou)

### 💾 Export
- Export do JPG (plné rozlišení)
- Exportuje všechna měření, dlahy a osteotomii
- Export preview režimu (s červeným klínem)

---

## 🚀 Instalace

### Varianta A: Stažení jednoho souboru
1. Stáhni `index.html`
2. Otevři v prohlížeči (doporučeno: Chrome, Firefox)
3. **To je všechno!** ✅


---


## 📋 Struktura menu (pravý panel)

Menu je seřazeno podle priority:

1. **🔪 Osteotomie** (nejvyšší priorita)
2. **📋 Vložené dlahy**
3. **📊 Naměřené úhly**
4. **📐 Naměřené vzdálenosti**
5. **📏 Kalibrace**
6. **📍 Aktuální body**
7. **📋 Instrukce**

---

## 💡 Tipy a triky

### Osteotomie
- **Close wedge** = rotace NAHORU (k tělu)
- **Open wedge** = rotace DOLŮ (od těla)
- Preview režim ukazuje červený klín **kde ještě JE kost** (před operací)
- Export v preview režimu vytvoří JPG pro prezentaci plánování

### Měření
- Drag & drop bodů pro přesné umístění
- Switch úhlu pokud potřebuješ reflex/non-reflex
- Každé měření má vlastní koš 🗑️

### Kalibrace
- Použij pravítko na snímku nebo známý rozměr implantátu
- Kalibrace platí pro všechna následující měření vzdáleností

---

## 🔒 Privacy & Security

- ✅ **100% offline** - žádná data neopouštějí počítač
- ✅ **Žádný server** - vše běží lokálně v prohlížeči
- ✅ **GDPR compliant** - žádné ukládání dat
- ✅ **Žádné závislosti** - jeden HTML soubor

---

## 🛠️ Technické informace

- **Jazyk:** HTML5 + JavaScript (vanilla)
- **Canvas API** pro vykreslování
- **Soubor:** ~160 KB (jeden soubor)
- **Prohlížeče:** Chrome, Firefox, Safari, Edge (moderní verze)
- **Offline:** Ano (po stažení)

---

## 🤝 Přispívání

Návrhy a bugreporty vítány! Otevři **Issue** nebo **Pull Request**.

---

## 📄 Licence

MIT License - použij, uprav, sdílej.

---

## 📞 Kontakt

karel.penicka@gmail.com

---

**Vytvořeno pro ortopedické chirurgy s láskou ❤️**
