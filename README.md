# sch-ma_Bdd_Projet1
Schéma Projet 1 CRM Hotêllerie



# Gestion commercial et achats :
   
   # Table:  Prestation 
   - id_Prestation
   - genre (séminaire, repas, buffet, linge)
   - nom
   - prénom
   - raison social ou privé
   - adresse
   - mail
   - téléphone
   - type (devis, commande ou facture)
 
  # Table:  Infos_prestation
  - id_Prestation
  - genre
  - prix_ht
  - quantité
  - tva
  - prix_total
  - status_Paiement

 # Table:  Dashboard
 - ca_Mois
 - liste_cinq_clients
 - evolution_Ca_six_moix


# Gestion incidents : 



  # Table:  Tickets
  - id_ticket
  - responsable (femme de chambre, réception)
  - description_incident
  - chambre_incident
  - type_incident (panne, fuite...)
  - urgence (faible, moderé, urgent)

 # Table:  Tâches
 - id_tache
 - description_tache
 - echeance_tache (date)
 - priorite_tache (faible, moderé, urgent)
 - status_tache (en attente, réparé)

 # Table:  Rapport
 - id_mois
 - nbr_tickets_ouverts
 - temps_reaction
 - class_liste_noir (les trois pires chambres en termes d'incidents)
 - liste_urgence
