# 🌐 Network Protocol Visualizer

**Une application interactive pour visualiser les communications réseau en temps réel**  
*Un outil pédagogique pour comprendre TCP, UDP et les échanges de paquets*

---

## ✨ Fonctionnalités

### 🎮 Core Features
- **Visualisation temps réel** des clients connectés
- **Animations fluides** des échanges de paquets
- **Simulation réaliste** des protocoles TCP/UDP
- **Journal complet** de toutes les communications

### 🧩 Protocoles Supportés
| Fonctionnalité | TCP ✅ | UDP ✅ |
|----------------|-------|-------|
| Accusés réception | ✓ | ✗ |
| Fiabilité | ✓ | ✗ |
| Contrôle flux | ✓ | ✗ |
| Perte paquets simulée | ✗ | ✓ (10%) |

### 🔧 Fonctions Avancées
- 🕹️ **Poignée de main TCP** (SYN, SYN-ACK, ACK)
- 📊 **Statistiques réseau** en temps réel
- 🔍 **Inspection détaillée** des paquets
- 🎨 **Visualisation colorée** :
  - 🔵 TCP
  - 🟢 UDP 
  - 🟡 ACK
  - 🔴 Paquets perdus

---

## 🛠️ Technologies

**Backend**  
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/-Socket.IO-010101?logo=socket.io&logoColor=white)

**Frontend**  
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Visualisation**  
![D3.js](https://img.shields.io/badge/-D3.js-F9A03C?logo=d3.js&logoColor=white)

---

## 🎯 Objectifs Pédagogiques

Ce projet permet de comprendre :
- 🧠 Les différences TCP/UDP
- 📦 La structure des paquets réseau
- ⏱️ Les délais de transmission
- 🔄 Le handshake TCP
- ❌ La gestion des paquets perdus

---

## Tips :

- Ouvrez plusieurs onglets pour simuler différents clients

- Utilisez l'interface pour envoyer des messages

- Observez les animations des paquets en temps réel

---

## 🚀 Installation & Utilisation

```bash
# 1. Installer les dépendances
npm install

# 2. Démarrer le serveur
npm run dev

# 3. Ouvrir dans le navigateur
http://localhost:3001 
