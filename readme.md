# Pflegeheim Ernährungsmanagement Crew

Dieses Projekt simuliert die interdisziplinäre Zusammenarbeit anhand der drei Berufsgruppen Pflegefachkraft, Arzt und Diätassistentin. Ein künstliches Team wird erzeugt, das einen Bewohner im Pflegeheim aufnimmt und einen Plan für die ersten 2 Wochen erstellt. 

## Projektbeschreibung
Mit CrewAI wurde eine Crew erstellt, die die Zusammenarbeit von Pflegefachkraft, Arzt und Diätassistentin simuliert. Am Beispiel von Herr Karl Maier, einem 85-jährigen Bewohner, wird gezeigt, wie die Berufsgruppen einen Pflege- und Ernährungsplan erstellen. Die Pflegefachkraft koordiniert den Ablauf, der Arzt erstellt ein medizinisches Statement, und die Diätassistentin erstellt einen Diätplan. Die Agenten können individuell erweitert und mit spezifischen Unterlagen versorgt werden.

## Installation
1. Klone das Repository:
    ```bash
    git clone https://github.com/goldikolb/Pflegeheim_Ernaehrungsmanagement_Crew.git
    ```
2. Wechsle in das Projektverzeichnis:
    ```bash
    cd Pflegeheim_Ernaehrungsmanagement_Crew
    ```
3. Erstelle eine virtuelle Umgebung und installiere die benötigten Pakete:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```
4. Erstelle eine `.env` Datei und füge deinen API-Key und den Serper API-Key hinzu.

## Verwendung
1. Starte das Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Öffne und führe `nutrtion_management_aessement.ipynb` aus.

## Funktionen
- Automatisierte Ernährungsanamnese bei Einzug eines Bewohners.
- Koordination des Ablaufs durch die Pflegefachkraft.
- Erstellung eines medizinischen Statements durch den Arzt.
- Erstellung eines Diätplans durch die Diätassistentin.

## Beispiel
### Fiktiver Bewohner
- **Anamnese**: Herr Karl Maier, 85 Jahre, 175cm, 65kg, mittelgradige Demenz, etc.
- **Medical**: Diagnosen: Mittelgradige Demenz, Herzinsuffizienz, etc.
- **Biografie**: Ernährungspräferenzen: deftig, kein Obst und Gemüse, etc.

## Autor
Christian Kolb

## Kontakt

Wenn Sie Fragen haben oder einen Beitrag leisten möchten, zögern Sie nicht, uns über unsere Webseite zu kontaktieren: [pflege-ai.de](https://pflege-ai.de/).

[![Website](https://img.shields.io/badge/Pflege--AI-Webseite-%230f0122?style=flat&logo=Web&logoColor=ff8154)](https://pflege-ai.de/)

## Follow me on Social Media

[![Threads](https://img.shields.io/badge/Threads-Follow%20me-blue?style=flat&logo=Thread&logoColor=white)](https://www.threads.net/@pflege_ki)

[![Twitter Follow](https://img.shields.io/twitter/follow/ai_fuerth?style=social)](https://twitter.com/ai_fuerth)

[![Instagram](https://img.shields.io/badge/Instagram-Follow%20@pflege__ki-blue?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/pflege_ki/)

## Support my work

[![Buy me a coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support%20Pflege_KI-FFDD00)](https://buymeacoffee.com/pflege_ki)
