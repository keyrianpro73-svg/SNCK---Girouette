PUPITRE SNCF — CoolLEDUX 01B4

CONTENU
- index.html : site web statique (Netlify/GitHub Pages)
- netlify.toml : configuration Netlify

DEPLOIEMENT NETLIFY
1. Décompresse ce ZIP.
2. Dans Netlify, choisis « Add new site » puis « Deploy manually ».
3. Glisse le dossier décompressé (celui qui contient index.html) dans la zone de dépôt.
4. Netlify publiera le site et donnera une adresse web.

POUR LE METTRE SUR GITHUB
1. Crée un dépôt GitHub.
2. Envoie index.html, netlify.toml et ce README à la racine du dépôt.
3. Dans Netlify, importe ce dépôt avec « Add new site » > « Import an existing project ».
4. Laisse le dossier de publication à la racine (.) et aucune commande de build.

IMPORTANT — BLUETOOTH
Cette version contient l'interface et une demande de sélection Bluetooth Web expérimentale.
Elle NE TRANSMET PAS encore les destinations à la barre : le protocole GATT CoolLEDUX
et le format des commandes de ton firmware doivent être identifiés et testés avant
d'activer l'envoi réel. Le bouton « Envoyer » prépare le texte sans prétendre l'avoir envoyé.

Web Bluetooth exige un contexte sécurisé (Netlify HTTPS) et un navigateur compatible.
La prise en charge varie selon le système et le navigateur. Un appareil peut être
sélectionné, mais cela ne garantit pas que le service GATT du panneau soit compatible.

Matériel communiqué :
- Nom dans CoolLED1248 : 01B4
- Modèle : CoolLEDUX
- Résolution : 64 × 16
- Adresse fournie : BE:27:4C:00:19:F8

Le champ « Prochain arrêt » reste uniquement dans l'interface du pupitre et n'est
jamais ajouté au texte préparé pour la barre.
