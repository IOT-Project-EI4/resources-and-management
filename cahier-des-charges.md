# Cahier des Charges  
## Projet IoT Smart Farming  

## 1. Introduction  
### 1.1 Contexte  
L’agriculture sous serre permet un meilleur contrôle des conditions climatiques et des ressources. L’objectif de ce projet est d’optimiser la gestion des paramètres environnementaux d’une serre grâce à un système IoT intelligent. Composé de capteurs autonomes, ce système permettra à l'utilisateur de suivre l'état de ses plantations à distance via interface web.  

### 1.2 Objectifs  
- Surveiller en temps réel les paramètres clés (température, humidité, luminosité, etc.)  
- Fournir une interface utilisateur pour la visualisation et le contrôle à distance  
- Optimiser la consommation d’énergie et d’eau  

### 1.3 Périmètre  
Ce projet concerne uniquement une serre de **[dimensions à préciser]**, équipée de capteurs connectés.  

---

## 2. Description du Besoin  
### 2.1 Fonctionnalités attendues  
- 📡 **Acquisition de données** : capteurs de température, humidité, CO₂, luminosité et d'image 
- 📲 **Communication** : transmission des données via LoRaWAN, Wi-Fi ou GSM  
- 📊 **Interface utilisateur** : application web/mobile pour supervision et alertes  

---

## 3. Contraintes  
### 3.1 Techniques  
- Microcontrôleur : **ESP32 / STM32 / autre**  
- Communication : **LoRa / Wi-Fi / GSM / BLE**  
- Alimentation : **Batterie + panneau solaire / secteur**  
- Logiciel : **Firmware embarqué + Backend cloud + Application web/mobile**  

### 3.2 Réglementaires  
- Respect des normes environnementales et électriques  
- Conformité aux réglementations IoT (GDPR, LPD, LoRaWAN OTAA, etc.)  

### 3.3 Budget  
- Coût matériel estimé : **[montant] €**  
- Développement logiciel : **[montant] €**  

---

## 4. Architecture du Système  
### 4.1 Schéma général  
![Schéma du projet](docs/ideas/draft.excalidraw)

### 4.2 Composants  
| Type | Composant | Quantité |  
|------|----------|----------|  
| Microcontrôleur | STM32F103RB | 1 |  
| Capteur Temp/Hum | DHT22 | 2 |  
| Capteur CO₂ | MH-Z19B | 1 |  
| Actionneur Pompe | Relais 5V | 1 |  
| Communication | Module LoRa SX1276 | 1 |  

---

## 5. Interfaces Utilisateur  
### 5.1 Dashboard  
- Graphiques temps réel  
- Alertes et notifications  
- Commande manuelle des actionneurs  

### 5.2 API et Cloud  
- API REST pour l’accès aux données  
- Stockage des mesures et historique  

---

## 6. Planification  
### 6.1 Étapes du projet  
1. 📌 **Étude et spécifications** (**[date]**)  
2. ⚙️ **Prototype électronique** (**[date]**)  
3. 💻 **Développement logiciel** (**[date]**)  
4. 🏗 **Tests et validation** (**[date]**)  
5. 🚀 **Déploiement** (**[date]**)  

### 6.2 Délais  
Durée estimée : **[nombre] mois**  

---

## 7. Risques et Solutions  
| Risque | Impact | Solution |  
|--------|--------|----------|  
| Perte de connectivité | 📉 Données non remontées | 📶 Redondance Wi-Fi/GSM |  
| Capteur défectueux | ⚠️ Données erronées | 🔄 Vérification régulière |  
| Sécurité des données | 🔒 Risque de piratage | 🔐 Chiffrement des communications |  

---

## 8. Conclusion  
Ce projet vise à démontrer comment l’IoT peut améliorer la gestion des serres agricoles en automatisant la collecte de données et le contrôle des paramètres environnementaux.  

---

## 9. Annexes  
- 📎 Documentation des capteurs et actionneurs  
- 📎 Schémas électroniques et PCB  
- 📎 Références techniques  

