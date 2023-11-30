# Infos et configs de mon pc ( novembre 2023 )
## _Liste des composants_
| Composants | Descriptions |
| ------ | ------ |
| Boitier | [Corsair 4000D Airflow blanc](https://www.topachat.com/pages/detail2_cat_est_micro_puis_rubrique_est_w_boi_sa_puis_ref_est_in20004228.html)  |
| Carte Mère | [MB GBT AMD AM5 B650 Gaming X AX](https://www.amazon.fr/dp/B0BKPTTHXM) |
| Processeur | [AMD Ryzen 5 7600 6-Core, 12-Thread Desktop Processor, up to 5.1GHz](https://www.amazon.de/dp/B0BMQJWBDM) |
| Mémoire | [CORSAIR VENGEANCE DDR5 RAM 32Go (2x16Go) 6000MHz CL30](https://www.amazon.fr/dp/B0C3RYHZJQ) |
| Stockage | [Western Digital Black SN770 M.2 2000 Go PCI Express 4.0 NVMe](https://www.pccomponentes.fr/western-digital-black-sn770-m2-2000-go-pci-express-40-nvme) |
| Carte graphique | [AMD Radeon RX 7900 XT 20 Go GDDR6 Sapphire Pulse](https://www.pccomponentes.fr/amd-radeon-rx-7900-xt-20-go-gddr6-sapphire-pulse) |
| Alimentation | [Seasonic Focus GX-850 850W 80 Plus Gold Modulaire](https://www.pccomponentes.fr/seasonic-focus-gx-850-850w-80-plus-gold-modulaire) |
| Radiateur | [Thermalright Peerless Assassin 120 CPU Air Cooler](https://www.amazon.fr/dp/B09NS9Z5BB) |
| Ventilateurs | [Thermalright TL-C12C X3 CPU Fan 120mm Case Cooler Fan](https://www.amazon.fr/dp/B0BQD467JL ) |

## _BIOS last update_
[B650 GAMING X AX (rev. 1.3)](https://www.gigabyte.com/fr/Motherboard/B650-GAMING-X-AX-rev-13/support#support-dl-bios)

## _OS_
- **ESP** ( UEFI boot FAT32 - secure boot OFF - csm OFF - only UEFI)
- **Microsoft Windows 10**
- **Endeavouros** :
   - [ISO version Galileo 11](https://endeavour.remi.lu/iso/Endeavouros-Galileo-11-2023.iso)
   - gestionnaire de fenêtres : [i3wm](https://i3wm.org/)

## _Partitionnement du disque_
- **ESP(UEFI)** : 500Mo ( 100 devraient suffire mais par sécurité 500)
- **Windows** : 499 Go
  - OS : NTFS 399 Go
  - Echange linux : NTFS 100 Go (Si problème avec [NTFS-3G](https://wiki.archlinux.org/title/NTFS-3G#Installation) FAT32 Ok)
- **Linux** : 1,5T 
  - SWAP : 64Go ( 2 X RAM ) SWAP
  - OS : 336Go EXT4
  - /home : 800Go EXT4
  - Sauvegardes : 300Go EXT4 

## _Questions_
- Partage de profils firefox - password( solutions locale opensource linux/windows ?)
- Solutions hébergements/diffusion vidéos ?
- Support supplémentaire si CG trop lourde/longue ?
