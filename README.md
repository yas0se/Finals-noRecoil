
# 🖱️ Mouse Macro Selector (WinAPI)

Ce projet est une interface graphique en C++ utilisant WinAPI, permettant à l'utilisateur de sélectionner une arme et de lancer une macro de tir automatique.

# Demo vide link: [Here](https://youtu.be/qCPxCBl5-ec)


# Modify your sense in code (ligne 2229) (mine is 84)

---

## 📁 Structure du projet

```
helloworld/
├── helloworld.cpp        // Code source principal (WinAPI + macros souris)
├── tasks.json            // Configuration build (G++)
├── launch.json           // Configuration Debug
├── settings.json         // Associe les fichiers système à C++
├── c_cpp_properties.json // Configuration IntelliSense
```

---

## ⚙️ Prérequis

- ✅ Visual Studio Code
- ✅ Extension C/C++ de Microsoft (`ms-vscode.cpptools`)
- ✅ [MSYS2](https://www.msys2.org/) avec :
  ```bash
  pacman -Syu
  pacman -S mingw-w64-ucrt-x86_64-gcc mingw-w64-ucrt-x86_64-gdb
  ```
- ✅ Ajoute `C:\msys64\ucrt64\bin` à ta variable `PATH`

---

## 🛠️ Compilation

Lance avec `Ctrl + Maj + B` dans VS Code (configuré via `tasks.json`).

Ou compile manuellement :
```bash
C:\msys64\ucrt64\bin\g++.exe -fdiagnostics-color=always -g helloworld.cpp -o helloworld.exe
```

---

## 🧪 Exécution & Débogage

### ▶ Méthode 1 : Exécution directe
```bash
./helloworld.exe
```


---

## ✅ Utilisation de l’interface

1. Sélectionne une arme (AK47, LewisGun, etc.)
2. Clique sur **Start Macro**
3. Pour arrêter, clique sur **Stop Macro**
