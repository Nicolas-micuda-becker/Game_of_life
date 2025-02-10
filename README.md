# Ordinateur Turing Complet sous Logisim  

Ce projet consiste en la création d'un ordinateur Turing-complet entièrement conçu à partir de portes logiques dans **Logisim**. Cet ordinateur est capable d'exécuter des programmes, et notamment une implémentation du **Jeu de la Vie** de Conway.

## 📜 Description du Projet  

L'objectif était de recréer, à partir des composants de base, un ordinateur fonctionnel incluant :  
- Une **unité de calcul** (ALU)  
- Une **unité de contrôle**  
- Une **mémoire RAM**  
- Un **programmeur d'instructions**  
- Un **affichage des résultats**  

Le tout a été conçu **sans utiliser de composants préfabriqués de Logisim**, uniquement avec des **portes logiques**, des **multiplexeurs**, et des **bascules**.

## 🎮 Le Jeu de la Vie  

Le **Jeu de la Vie** est un automate cellulaire où une grille de cellules évolue selon des règles simples. Sur cet ordinateur, il est implémenté sous forme d'un programme stocké en mémoire et exécuté par l'unité de contrôle.

## 🚀 Comment Tester ?  

### 🛠 **Installation de Logisim**  
Assurez-vous d'avoir **Logisim** installé sur votre machine. Vous pouvez le télécharger ici :  
🔗 [Logisim Download](https://sourceforge.net/projects/circuit/)  

### ▶️ **Lancer le programme**  
1. **Ouvrir le fichier `Game_of_Life.circ`** dans Logisim.  
2. **Charger le programme en RAM** :  
   - Accédez au **premier module de RAM**.  
   - Importez le fichier **RAM1** (qui contient le programme).  
3. **Démarrer l'horloge** :  
   - Dans **Simulate > Tick Frequency**, choisissez une **fréquence adaptée**.  
   - Activez l'horloge pour voir le jeu se dérouler.  

## 🖥️ Aperçu  

Une fois lancé, le programme exécutera le **Jeu de la Vie** et mettra à jour l'affichage en fonction des cycles de calcul.

## 📄 Licence  

Projet libre d'utilisation et de modification.  

---
