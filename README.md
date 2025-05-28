# roboshop-ansible


SOP :
    1) Code should be dry 
    2) Secrets should be coming up from vault 
    3) Re-run of playbook should work.

> User, Cart, Catalogue are nodeJS components and their installation instructuons are same.     
  * What if in future if 5 more nodejs components comes up ? 
  * Identify the common pattern for nodejs and place them in a common role
  * Then import them whereever it's needed.