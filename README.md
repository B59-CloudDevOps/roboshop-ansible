# roboshop-ansible


SOP :
    1) Code should be dry 
    2) Secrets should be coming up from vault 
    3) Re-run of playbook should work.

> User, Cart, Catalogue are nodeJS components and their installation instructuons are same.     
  * What if in future if 5 more nodejs components comes up ? 
  * Identify the common pattern for nodejs and place them in a common role
  * Then import them whereever it's needed.
  
> Right now, we just have one java component which is shipping & one python component which is payment.
  * Keeping the future java or payment components in to consideration, I would like to write common files


> roboshop
    1) Running TF to create the infra.
    2) playing the ansible-playbooks to make the configuration management. 

    With a sinle click I want the whole infra