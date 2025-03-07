# digital-detox
# Digital Detox Companion

Eine Static Web App, die tägliche Offline-Herausforderungen bietet, um digitale Überlastung zu reduzieren und ein bewussteres Leben zu fördern.

![Digital Detox Companion Screenshot](https://i.imgur.com/OyXcwCd.png)

## 🌟 Features

- **Tägliche Herausforderungen**: Entdecke über 100 verschiedene Offline-Aktivitäten.
- **Kategorien**: Herausforderungen in 8 verschiedenen Kategorien (Achtsamkeit, Sozial, Kreativität, Natur, Körperlich, Produktivität, Lernen, Erholung).
- **Fortschrittsverfolgung**: Sammle Punkte, steige im Level auf und baue einen Streak auf.
- **Abzeichen und Erfolge**: Schalte Abzeichen für deine Leistungen frei.
- **Einstellungen**: Passe die App an deine Bedürfnisse an.
- **Vollständig offline-fähig**: Alle Daten werden lokal im Browser gespeichert, keine Serveranbindung erforderlich.
- **PWA-kompatibel**: Kann als Progressive Web App auf Mobilgeräten installiert werden.
- **Responsive Design**: Funktioniert auf allen Geräten, vom Smartphone bis zum Desktop.

## 📱 Monetarisierungsmöglichkeiten

Die App kann auf verschiedene Arten monetarisiert werden:

1. **Freemium-Modell**: 
   - Kostenlose Basis-Version mit begrenzten Herausforderungen
   - Premium-Version mit Zugang zu allen Herausforderungen und Funktionen

2. **Abonnement-Modell**:
   - Monatliches/Jährliches Abonnement für kontinuierlichen Zugang zu neuen Herausforderungen

3. **In-App-Käufe**:
   - Zusätzliche Herausforderungspakete
   - Spezielle Abzeichen und Designs

4. **White-Label-Lösung**:
   - Verkauf an Unternehmen für ihre Mitarbeiter als Teil eines Wellness-Programms

## 🚀 Installation

1. **Repository klonen**

```bash
git clone https://github.com/dein-username/digital-detox-companion.git
cd digital-detox-companion
```

2. **Abhängigkeiten installieren**

```bash
npm install
# oder
yarn install
```

3. **Entwicklungsserver starten**

```bash
npm run dev
# oder
yarn dev
```

4. **Produktions-Build erstellen**

```bash
npm run build
# oder
yarn build
```

## 💻 Technologie-Stack

- **Frontend**: Next.js mit Tailwind CSS
- **Datenspeicherung**: LocalStorage (keine Datenbank erforderlich)
- **PWA-Unterstützung**: Service Worker für Offline-Funktionalität und App-Installation

## 🔧 Anpassung

### Herausforderungen anpassen

Du kannst die Herausforderungen in der Datei `src/data/challenges.js` anpassen. Füge einfach neue Herausforderungen zum Array hinzu oder ändere bestehende:

```javascript
{
  id: "unique-id",
  title: "Herausforderungstitel",
  description: "Beschreibung der Herausforderung",
  category: "mindfulness", // Eine der definierten Kategorien
  difficulty: "beginner", // beginner, intermediate, advanced, expert
  duration: "short", // short, medium, long, extended
  points: 15, // Punktewert
  image: "/images/challenges/your-image.jpg" // Optionales Bild
}
```

### Design anpassen

Das Design kann in der Datei `tailwind.config.js` angepasst werden. Ändere die Farbpalette und andere Designelemente nach deinen Vorstellungen:

```javascript
theme: {
  extend: {
    colors: {
      primary: {
        50: '#f0f9ff',
        // ... weitere Farben
        900: '#0c4a6e',
      },
      // ... weitere Farbpaletten
    },
  }
}
```

## 📄 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe die [LICENSE](LICENSE) Datei für Details.

## 🙏 Danksagungen

- Icons von [Feather Icons](https://feathericons.com/)
- Hintergründe und Design-Inspiration von [Unsplash](https://unsplash.com/)
