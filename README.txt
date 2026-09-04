CONSTANTINE — PROJET ANDROID

Le dossier www contient l'application web prête à être emballée avec Capacitor.

Fonctionnement:
- paquet de base = cartes 01 à 20
- paquet Planification future = cartes 21 à 30
- une seule carte visible
- swipe gauche/droite = tirage suivant
- Marché noir ou Atelier du paquet de base => une carte Future est automatiquement mise en défausse
- boutons Mélanger et Recommencer

Pour compiler sur Windows avec Capacitor:
1. Ouvrir PowerShell dans ce dossier.
2. npm init -y
3. npm install @capacitor/core @capacitor/cli @capacitor/android
4. npx cap init Constantine com.jeanboucher.constantine --web-dir www
5. npx cap add android
6. npx cap sync android
7. npx cap open android
Puis Android Studio: Build > Generate App Bundles or APKs > Generate APKs.
