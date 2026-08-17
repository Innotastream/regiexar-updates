# Canal candidate

## Test Windows corrigé

1. Télécharger et extraire entièrement `bootstrap/Xar-Tsaroth-Regie-v1.9.2-ONLINE-BOOTSTRAP-CANDIDATE.zip`.
2. Lancer `start-windows.bat`.
3. Le mini-installateur doit accepter les métadonnées inoffensives `desktop.ini` et nommer tout véritable écart d’intégrité.
4. Le launcher doit détecter la 1.9.3 publiée dans `latest.json`.
5. Choisir **Installer la mise à jour**.
6. Après relance, la version discrète du launcher doit indiquer `v1.9.3 candidate`.

Les anciens artefacts 1.9.0 et 1.9.1 restent conservés. Le nouveau bootstrap et le paquet final ont été construits depuis une source propre, extraits dans des dossiers neufs et retestés. Les données utilisateur restent hors du répertoire programme.
