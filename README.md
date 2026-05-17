# isy-bedienkonzept

Dieses Repository enthält das Antora-Modul für die Dokumentation des ISY **Bedienkonzepts**.

Das Bedienkonzept ist nicht nur ein Dokument mit Vorgaben für das Frontend-Design.
Es ist ein umfassender Rahmen, der die Grundlage für die Entwicklung einer konsistenten und benutzerfreundlichen Oberfläche schafft.
Durch gemeinsame Standards und Best Practices unterstützt es Ziele wie eine höhere Benutzerzufriedenheit, effizienteres Arbeiten und eine stärkere Markenidentität.

Das zentrale Ziel ist es, die User Experience zu verbessern und die Zufriedenheit sowie Produktivität der Anwenderinnen und Anwender zu maximieren.
Sie sollen mit dem Frontend reibungslos arbeiten und ihre Ziele effizient erreichen können.

Die Kapitel sind nach dem Prinzip „vom Kleinen zum Großen“ aufgebaut:

1. Allgemeiner Rahmen und übergreifende Prinzipien
2. Basiselemente, zum Beispiel Texte und Farben
3. Bedienelemente als kleinste Interaktionselemente
4. Entwurfsmuster als Kombinationen aus Basiselementen und Bedienelementen
5. Vollständige Anwendungsfälle, die aus diesen Mustern aufgebaut sind

Für die in dieser Dokumentation beschriebenen Vorgaben steht eine Referenzimplementierung („Live-Demo“) zur Verfügung.

## Lokale Antora-Ausführung

Dieses Modul wird üblicherweise von einem separaten Repository verwendet, das die vollständige Dokumentationswebsite baut.
Für die lokale Arbeit enthält dieses Repository ein schlankes Antora-Setup, mit dem dieses einzelne Modul gebaut und in der Vorschau angezeigt werden kann.

### Voraussetzungen

- Node.js LTS Latest
- npm

### Abhängigkeiten installieren

```zsh
npm install
```

### Lokale Website bauen

```zsh
npm run docs:build
```

### Generierte Website lokal bereitstellen

```zsh
npm run docs:serve
```

Öffne anschließend `http://localhost:8080` im Browser.

### Bauen und Bereitstellen in einem Schritt

```zsh
npm run docs:preview
```

## Ausgabe

- Generierte Website: `build/site/`