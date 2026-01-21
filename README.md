# sch-ma_Bdd_Projet1
Schéma Projet 1 CRM Hotêllerie



# Gestion commercial et achats :
   
   # Table:  Document 
   - id_document
   - id_contact (FK)
   - genre (séminaire, repas, buffet, linge)
   - type (devis, commande ou facture)

  # Table:  Contact
  - id_contact
  - type (client, fournisseur)
  - nom
  - adresse
  - raison social ou privé
  - adresse
  - mail
  - téléphone

  # Table:  Document_line
  - id_Prestation
  - id_document (FK)
  - id_product (FK) 
  - genre
  - quantité
  - status_Paiement

  # Table:  Product
  - id_product
  - libelle_product
  - prix_ht
  - tva
  - prix_ttc

 # Table:  Dashboard
 - sum_facture_mois
 - liste_cinq_clients
 - evolution_Ca_six_moix
