# Koordinatentransformation mit REFRAME-Dienst von swisstopo

Mithilfe der WebApp kann eine Transformation von Koordinaten gerechnet werden.

## Getting Started

1. Repository klonen:

   ```
   git clone
   ```

   Alternativ kann auch mithilfe des Github-Desktop das Repository geklont werden

2. `node.js`-Module installieren:

   ```
   npm install
   ```

3. Webserver starten

   ```
   npm run dev
   ```

4. Auf den angezeigten localhost-Link klicken und die Webseite öffnen

## Funktionsweise

Mithilfe des gewählten Transformators können Koordinaten aus den Inputfelder auf Knopfdruck in ein anderes Koordinatensystem gewechselt werden.

Die Transformation funktioniert auf Basis der REST API von swisstopo. Die Sokumentation kann hier eingesehen werden:

<https://www.swisstopo.admin.ch/en/rest-api-geoservices-reframe-web>
