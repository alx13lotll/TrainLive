# TrainLive – horaires SNCB en direct + IA

## Obtenir ton APK (sans rien installer)
1. Crée un compte sur github.com, puis un nouveau dépôt (New repository), par exemple `trainlive`.
2. Sur la page du dépôt : Add file > Upload files. Glisse TOUT le contenu du dossier (y compris le dossier caché `.github`, `www`, `package.json`, `capacitor.config.json`). Clique Commit changes.
3. Onglet Actions > "Build APK" : attends ~5 minutes (coche verte).
4. Clique sur la ligne terminée > en bas "Artifacts" > `TrainLive-apk` > télécharge, dézippe.
5. Envoie `app-debug.apk` sur ton téléphone Android, ouvre-le et autorise l'installation (sources inconnues).

## Assistant IA
Onglet IA > colle ta clé API Anthropic (console.anthropic.com). Elle reste sur ton téléphone.

## Données
Horaires et temps réel : API gratuite iRail (api.irail.be), basée sur les données SNCB.
