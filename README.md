# Ajout et montage d'un disque dur sur proxmox


**Dans VirtualBox, sur le contrôleur SATA existant, création d'un disque dur de type VMDK**   

![image](https://github.com/techerbeatrice/ajout_montage_disque-dur_proxmox/assets/138071140/e5637e58-172e-4c69-8700-08b2a7ebea8a)    
       
![image](https://github.com/techerbeatrice/ajout_montage_disque-dur_proxmox/assets/138071140/00cb5568-0096-4013-ac01-2d069676487d)

____________

**2ème disque dur ajouté visible dans la GUI**

![image](https://github.com/techerbeatrice/ajout_montage_disque-dur_proxmox/assets/138071140/40a74a07-1045-4cca-8214-74426890a1a7)
____________

**En shell, formatage et montage**
**voir les informations sur ce 2ème disque dur**   

![image](https://github.com/techerbeatrice/ajout_montage_disque-dur_proxmox/assets/138071140/6ce80d8a-353b-4e88-b275-2710def5797b)

**partionner ce disque dur**

![image](https://github.com/techerbeatrice/ajout_montage_disque-dur_proxmox/assets/138071140/f6ca0d8f-9765-4348-8afb-80db9c1a0e31)

**Formater cette partition en _ext4_ et la monter dans un dossier /srv/dd1**   

![image](https://github.com/techerbeatrice/ajout_montage_disque-dur_proxmox/assets/138071140/72f88839-5421-45f6-8e06-64c645e7f441)

![image](https://github.com/techerbeatrice/ajout_montage_disque-dur_proxmox/assets/138071140/4829c3a1-1007-48a4-8c8a-5fc089d6bdd8)

![image](https://github.com/techerbeatrice/ajout_montage_disque-dur_proxmox/assets/138071140/384720af-a9f9-4e56-996d-bc776576ffc6)
