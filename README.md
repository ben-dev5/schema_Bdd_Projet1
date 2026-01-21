# sch-ma_Bdd_Projet1
Schéma Projet 1 CRM Hotêllerie



# Gestion commercial et achats :
   
   # Table:  sales_order 
   - id_sales_order
   - id_contact (FK)
   - genre (séminaire, repas, buffet, linge)
   - type (devis, commande ou facture)

  # Table:  Contact
  - id_contact
  - type (client, fournisseur)
  - nom
  - prénom
  - adresse
  - raison social ou privé
  - mail
  - téléphone

  # Table:  Invoice
  - id_invoice
  - id_contact (FK)
  - nom
  - adresse 
  - raison social ou privé 
  - mail 
  - téléphone
  - id_product 
  - libelle_product 
  - prix_ht 
  - tva 

  # Table:  sales_order_line
  - id_sales_order_line
  - id_sales_order (FK)
  - id_product (FK)
  - id_contact (FK)
  - genre
  - quantité
  - date
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
