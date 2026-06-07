# Play Store â€” NH Liberdade - Formulaire

1. Publier sur **GitHub Pages** (HTTPS obligatoire)
2. Ouvrir `https://VOTRE_USER_GITHUB.github.io/nh-liberdade-transfers/PC/formulario/` dans Chrome â†’ **Installer l'application**
3. VÃ©rifier : `https://VOTRE_USER_GITHUB.github.io/nh-liberdade-transfers/PC/formulario/.well-known/assetlinks.json`
4. [PWABuilder](https://www.pwabuilder.com/) â†’ coller l'URL â†’ **Package for Android** â†’ AAB
5. Play Console â†’ crÃ©er l'app â†’ package `io.github.nhcollection_lisboa.formulario_pc`
6. Mettre Ã  jour le **SHA-256** dans `.well-known/assetlinks.json` et `google-play/assetlinks.json`

Package : `io.github.nhcollection_lisboa.formulario_pc`