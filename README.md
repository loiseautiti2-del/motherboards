# ASUS PRIME B660M-A — Fiche complète

## Informations générales
- **Marque** : ASUS  
- **Modèle** : PRIME B660M-A  
- **Gamme** : PRIME (grand public / bureautique / polyvalent)  
- **Format** : Micro-ATX (mATX)  
- **Année de sortie** : 2022  

---

##Processeur (CPU)
- **Socket** : LGA 1700  
- **Chipset** : Intel B660  

###CPU compatibles
- Intel Core **12ᵉ génération** (Alder Lake)  
- Intel Core **13ᵉ génération** (Raptor Lake) ⚠️ *BIOS à jour requis*

###CPU non compatibles
- Intel Core **10ᵉ / 11ᵉ génération**
- Intel **Xeon**

> **Pas d’overclocking CPU** (limitation du chipset B660)

---

## Mémoire (RAM)
- **Type** : DDR4  
- **Slots** : 4  
- **Capacité maximale** : 128 Go  
- **Fréquences supportées** :  
  - DDR4-2133 → DDR4-3200  
- **Dual-Channel** : Oui  
- **ECC** : Non  

---

## Carte graphique (GPU)
- **Slot principal** :  
  - 1× PCIe 4.0 x16  

### Compatibilité GPU
- NVIDIA (GTX / RTX)  
- AMD Radeon  

- **Multi-GPU** :  Non (pas de SLI / CrossFire)

---

## Stockage
- **M.2** :  
  - 2× M.2 NVMe PCIe 4.0  
- **SATA** :  
  - 4× SATA III (6 Gb/s)  
- **RAID** :  
  - SATA RAID 0 / 1 / 5 / 10  

---

## Connectique

### Arrière (I/O)
- USB 3.2 Gen 2  
- USB 3.2 Gen 1  
- USB 2.0  
- HDMI  
- DisplayPort  
- Ethernet 2.5 Gb  
- Prises audio (jack)

###Interne
- Connecteurs USB pour façade  
- Headers RGB / ARGB  
- Connecteurs ventilateurs (CPU + boîtier)

---

## Réseau & Audio
- **Ethernet** : Realtek 2.5 Gb  
- **Wi-Fi** : ❌ (sauf version *WiFi*)  
- **Bluetooth** : ❌  
- **Audio** : Realtek 7.1  

---

##Alimentation
- **Connecteurs** :
  - 24-pin ATX  
  - 8-pin CPU  

### CPU recommandés
- Jusqu’à **Intel Core i7** : ✔️ OK  
- **Intel Core i9** : ⚠️ possible mais non idéal (VRM limité)

---

## ⚠️ Problèmes connus & solutions

### Problème 1 — Démarrage impossible avec CPU 13ᵉ gen
- **Cause** : BIOS trop ancien  
- **Solution** : Mettre à jour le BIOS

---

### Problème 2 — RAM bloquée à 2133 MHz
- **Cause** : Profil XMP désactivé  
- **Solution** : Activer XMP dans le BIOS

---

###Problème 3 — Pas de Wi-Fi
- **Cause** : Version sans module Wi-Fi  
- **Solution** :  
  - Carte Wi-Fi PCIe  
  - Ou adaptateur Wi-Fi USB
