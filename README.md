# 📌 ToDoApp - React Native 

## 🎯 Objectif  

ToDoApp est une **application mobile** de gestion de tâches développée en **React Native** avec Expo. Ce projet a été conçu en **auto-didacte** pour explorer le développement d'applications mobiles, l'utilisation des hooks en React (useState) et la gestion de l'affichage des listes dynamiques avec FlatList.

## 🚀 Aperçu du Portfolio

<div style="text-align: center;">  
<img src="assets/images/preview.jpg" width="40%" alt="Aperçu de l'application"/>  
</div>

## 💡 Fonctionnalités

✅ Ajouter une tâche 📌  
✅ Liste des tâches enregistrées 📋  
✅ Suppression des tâches terminées ❌

## 🛠️ Technologies utilisées  

- **React Native** : Framework pour applications mobiles.
- **Expo** : Facilite le développement et le test sur mobile.
- **JavaScript** : Langage de programmation relié à React Native.

## 🎯 Objectifs  

✅ Comprendre les bases du développement mobile avec **React Native**.  
✅ Utiliser **Expo** pour simplifier le déploiement et le test de l'application.  
✅ Manipuler les hooks d'état avec useState pour gérer les tâches.  
✅ Gérer des listes dynamiques avec FlatList.  
✅ Expérimenter le test sur un téléphone via **Expo Go**.

## 🚀 Installation et exécution

### 1️⃣ Cloner le projet depuis GitHub

```bash
git clone https://github.com/enzo-mensier/ToDoApp.git
cd ToDoApp
```

### 2️⃣ Installer les dépendances

```bash
npm install
```

### 3️⃣ Lancer l'application

#### 🟢 Option 1 : Tester sur un téléphone (Wi-Fi recommandé)

Assurez-vous que votre téléphone et votre PC sont connectés au même réseau **Wi-Fi**.

```bash
npx expo start --lan
```

Ensuite :
- Ouvrez **Expo Go** sur votre téléphone 📱.
- Scannez le QR Code affiché dans le **terminal**.
- L'application se lancera **automatiquement**.

#### 🔵 Option 2 : Tester en USB (si Wi-Fi indisponible)

1. Activez le **mode développeur** et le débogage USB sur votre téléphone Android.
2. Branchez votre téléphone en **USB**.
3. Vérifiez la connexion avec :
```bash
adb devices
```
4. Lancez Expo en tunnel pour un accès stable :
```bash
npx expo start --tunnel
```
5. Ouvrez Expo Go, entrez l'URL fournie dans le **terminal**.

#### 🟠 Option 3 : Tester sur un émulateur Android

Si vous avez Android Studio et un émulateur installé, lancez simplement :
```bash
npx expo start
```
Puis sélectionnez **"Run on Android device/emulator"**.