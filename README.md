# Documentation : Création d'une Unité d'Organisation, d'un Groupe et d'un Utilisateur dans Active Directory  


## Étape 1 : Créer une Unité d'Organisation (OU)  

1. Ouvrir **Utilisateurs et ordinateurs Active Directory**.  
2. Clic droit sur le domaine `wilders.lan` > **Nouveau** > **Unité d'organisation**.  
3. Nommer l'OU : `Wilders_students`.  
4. Valider avec **OK**.  

---

## Étape 2 : Créer un Groupe d'Utilisateurs  

1. Naviguer dans l'OU `Wilders_students`.  
2. Clic droit sur `Wilders_students` > **Nouveau** > **Groupe**.  
3. Configurer :  
   - **Nom** : `Students`.  
   - **Portée** : **Global**.  
   - **Type** : **Sécurité**.  
4. Valider avec **OK**.  

---


## Ajouter l'utilisateur au groupe Students  

1. Clic droit sur `User1` > **Propriétés**.  
2. Onglet **Membre de** > **Ajouter** > `Students`.  
3. Valider avec **OK**.  

