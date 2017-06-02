# mongodb-seeding

Beispielprojekt, welches das Befüllen einer MongoDB mit Testdaten aufzeigt

## Ausprobieren

```sh
git clone git@github.com:ifi-sose17/mongodb-seeding.git

cd mongodb-seeding

#
# 1. Schritt
#
# Abhängigkeiten installieren
#
npm install

#
# 2. Schritt
# 
# MongoDB Instanz via Docker starten
#

# 3. Schritt
#
# Port Eurer Instanz in der Datei `seed.json` hinterlegen.
#

#
# 4. Schritt
#
# Seeding starten
#

NODE_ENV=dev npm run import
```

Im Anschluss befinden sich die in `seeds` definierten Testdaten in der Datenbank.
