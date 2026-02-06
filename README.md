# Portfolio Website - Dokumentation

## 📁 Projektstruktur

```
portfolio/
├── index.html          # Haupt-HTML-Datei
├── css/                # CSS-Dateien
│   ├── variables.css   # Farben & CSS-Variablen
│   ├── base.css        # Basis-Styles & globale Elemente
│   ├── header.css      # Header & Navigation
│   ├── hero.css        # Hero-Sektion
│   ├── about.css       # Über-mich-Sektion
│   ├── education.css   # Ausbildungs-Sektion
│   ├── projects.css    # Projekte-Sektion
│   ├── documents.css   # Dokumente-Sektion
│   ├── testimonials.css# Referenzen-Sektion
│   ├── contact.css     # Kontakt-Sektion
│   ├── footer.css      # Footer
│   └── responsive.css  # Responsive Design
├── js/                 # JavaScript-Dateien
│   └── main.js         # Haupt-JavaScript-Datei
└── assets/             # Bilder & Dateien (leer - für deine Dateien)
```

## 🎨 Features

- ✨ **Dark/Light Mode** mit automatischer Speicherung
- 📱 **Vollständig responsiv** (Desktop, Tablet, Mobile)
- 🎯 **Alle Portfolio-Sektionen** enthalten
- 🚀 **Moderne Animationen** und Hover-Effekte
- 💼 **Professionelles Design**

## 🛠️ Personalisierung

### 1. Persönliche Daten ändern
Öffne `index.html` und ersetze folgende Platzhalter:

- **Name**: "Max Mustermann" → Dein Name
- **Titel**: "Full-Stack Developer & UI/UX Designer" → Deine Berufsbezeichnung
- **Logo**: "MM" → Deine Initialen
- **Kontaktdaten**: E-Mail, Telefon, LinkedIn, GitHub Links

### 2. Profilbild austauschen
In `index.html`, Zeile mit `<img src="..."` finden und URL ersetzen:
```html
<img src="dein-profilbild.jpg" alt="Profilbild" class="profile-photo">
```

### 3. Farben anpassen
Öffne `css/variables.css` und ändere die Farbwerte:
```css
--accent: #2563eb;        /* Hauptfarbe */
--accent-hover: #1d4ed8;  /* Hover-Farbe */
```

### 4. Projekte hinzufügen/bearbeiten
In `index.html` die `.project-card` Blöcke bearbeiten:
```html
<div class="project-card">
    <div class="project-image">🚀</div>
    <div class="project-content">
        <h3>Dein Projekt-Name</h3>
        <p>Beschreibung...</p>
        ...
    </div>
</div>
```

### 5. Ausbildung anpassen
Die `.education-item` Blöcke in `index.html` bearbeiten

### 6. Dokumente verlinken
Ersetze `#` durch echte Download-Links:
```html
<a href="pfad/zu/deinem/lebenslauf.pdf" class="document-card" download>
```

## 📂 Dateien organisieren

Lege deine Dateien im `assets/` Ordner ab:
```
assets/
├── images/
│   └── profilbild.jpg
├── documents/
│   ├── lebenslauf.pdf
│   ├── master-zeugnis.pdf
│   └── bachelor-zeugnis.pdf
└── ...
```

## 🚀 Website starten

1. Öffne `index.html` in einem Webbrowser
2. Oder hoste die Dateien auf einem Webserver

## 💡 Tipps

- **Dark Mode**: Der Theme-Status wird im Browser gespeichert
- **Mobile Navigation**: Funktioniert automatisch auf kleinen Bildschirmen
- **Smooth Scroll**: Klicke auf Menü-Links für sanftes Scrollen
- **Anpassbar**: Alle Farben sind in `variables.css` zentral definiert

## 🎯 Browser-Kompatibilität

- ✅ Chrome/Edge (neueste Versionen)
- ✅ Firefox (neueste Versionen)
- ✅ Safari (neueste Versionen)
- ✅ Mobile Browser

## 📝 Lizenz

Frei verwendbar für persönliche Portfolio-Websites.

---

**Viel Erfolg mit deinem Portfolio! 🎉**
