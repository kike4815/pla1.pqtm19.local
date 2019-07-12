# _ Configuració entorn en desenvolupament Web _
---
## _Introducció_

| LLista del contingut del document |

|:------------------------------------:|

| 1.Instal·lació Xampp |

|2.Configuració Virtual Host d'Apache|

|3.Instal·lació de Eclipse|

|4.Definició de WorkSpace|

|5.Definició de Projecte|

|6.Definició de Repositori local|

|7.Creació de Repositori de GitHub|

|8.Exportació de la branca "master" local sobre repositori GitHub|

###  1.Instal·lació Xampp

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/Install_Xampp.PNG)  

 el primer pas que hem de fer és anar a la pàgina de Xampp i fer la descàrrega  
 
![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/2Install_Xampp.PNG)  
  
una vegada l'hem descarregat toca **obrir** l'arxiu executable  


![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/3Install_Xampp.PNG)  

veurem un missatge d'avís, cliquem endavant

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/4Install_Xampp.PNG)  

comença el SETUP!

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/5Install_Xampp.PNG)  

instal·lem per defecte les opcions que ens dóna..

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/6Install_Xampp.PNG)  

**IMPORTANT:** tenir ben ubicat l'arxiu Xampp

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/7Install_Xampp.PNG)  

desmarquem la pestanya de lectura (ja ho mirarem més endavant ;)

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/8Install_Xampp.PNG)  

preparats per la instal·lació en 3,2,1..

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/9Install_Xampp.PNG)  

instal·lant, ja ho tenim

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/10Install_Xampp.PNG)  

ara toca el Panel de control

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/11Install_Xampp.PNG)  

En anglès si no volem apendre alemany (proper capítol)

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/12Install_Xampp.PNG)  

marquem les caselles de Apache i MySQL perquè comencin a treballar...

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/13Install_Xampp.PNG)

com podem veure, tot funciona correctament amb els ports oberts "escoltant"

![lo primer que hem de fer és anar a la pàgina de Xampp i fer la descàrrega](./media/Xampp/14Install_Xampp.PNG)  




### 2.Configuració Virtual Host d'Apache

Anem a crear la carpeta on  volem el **directori Arrel**:  

![aquí va la primera imatge](./media/virtualhost/1.PNG)   

ara haurem d'anar al directori http.vhosts.config per crear el servidor virtual:

![aquí va la primera imatge](./media/virtualhost/2.PNG)    

L'editem amb click dret i el Notepadd++

![aquí va la primera imatge](./media/virtualhost/3.PNG)  

Hem marcat amb color groc les linees a modificar (recordem l'arxiu creat anteriorment)    

![aquí va la primera imatge](./media/virtualhost/4.PNG)  

Aprofitem un Virtual Host que teniem anteriorment creat i modifiquem el directori corresponent    

![aquí va la primera imatge](./media/virtualhost/5.PNG)  

ens falta definir la dir-li al nostre servidor com es dira la pàgina:    

![aquí va la primera imatge](./media/virtualhost/6.PNG)  

En la següent imatge ens salta l'avís de que hem de modificar-ho com administrador, sense cap problema..    

![aquí va la primera imatge](./media/virtualhost/7.PNG)  

Per comprovar que tot funciona primerament hem de reiniciar el Apache    

![aquí va la primera imatge](./media/virtualhost/8.PNG)  

Ja està reiniciat i sembla que de moment funciona (el Apache i el MySQL estan escoltant així que bona senyal)    

![aquí va la primera imatge](./media/virtualhost/9.PNG)  

entrem a la nostra pàgina web i...    

![aquí va la primera imatge](./media/virtualhost/10.PNG)   

>>ja la tenim!!!!


### 3.Instal·lació de Eclipse

Lo primer és instal·lar el programa _Eclipse_:

![primera foto](./media/Eclipse/Install_Eclipse/1.PNG)  
  
descarreguem la versió 64 bit
  
![primera foto](./media/Eclipse/Install_Eclipse/2.PNG)  

Cliquem a Download:  

![primera foto](./media/Eclipse/Install_Eclipse/3.PNG)  

Esperem a descarregar-ho i obrim l'arxiu executable  

![primera foto](./media/Eclipse/Install_Eclipse/4.PNG)  

És necessari que descarreguem l'arxiu de Java ja que treballen junts els dos programes:  

![primera foto](./media/Eclipse/Install_Eclipse/5.PNG)  

Acceptem llicencia i endavant!  

![primera foto](./media/Eclipse/Install_Eclipse/6.PNG)  

Ja el tenim descarregat i ara es quan toca executar-ho  

![primera foto](./media/Eclipse/Install_Eclipse/7.PNG)  

Comencem amb l'instal·lador fent Next:  

![primera foto](./media/Eclipse/Install_Eclipse/8.PNG)  

La ubicació de l'arxiu per defecte és correcte  

![primera foto](./media/Eclipse/Install_Eclipse/9.PNG)  


![primera foto](./media/Eclipse/Install_Eclipse/10.PNG)  

i acabem tancant una vegada descarregats tots els arxius 


![primera foto](./media/Eclipse/Install_Eclipse/11.PNG)  

S'obre el programa i escollim l'opció de PHP (com veiem hi ha de tot tipus)  

![primera foto](./media/Eclipse/Install_Eclipse/12.PNG)  
  

**ALERTA:**  **instal·lar l'Eclipse al Directori on tenim els projectes que volem crear i modificar per no tenir que dir-li en tot moment la ruta on buscar-los**


![primera foto](./media/Eclipse/Install_Eclipse/13.PNG)  

Acceptem les condicions que ens ofereix el programa  

![primera foto](./media/Eclipse/Install_Eclipse/14.PNG)  

i Instal·lem..  

![primera foto](./media/Eclipse/Install_Eclipse/15.PNG)  


![primera foto](./media/Eclipse/Install_Eclipse/16.PNG)  



![primera foto](./media/Eclipse/Install_Eclipse/17.PNG)  

Ara només hem de Iniciar l'Eclipse:    

![primera foto](./media/Eclipse/Install_Eclipse/18.PNG)  

![primera foto](./media/Eclipse/Install_Eclipse/19.PNG)  

i acabem **definint** el Espai de Treball de Eclipse:  

![primera foto](./media/Eclipse/Install_Eclipse/20.PNG)

### 4.Definició de WorkSpace

El workspace es la carpeta on es guardaran tots els arxius que generi Eclipse, tant codi font como codi compilat i codi del propi Eclipse.

![./media/Eclipse/Workspace.PNG](./media/Eclipse/Workspace.PNG)  


### 5.Definició de Projecte  

![./media/Eclipse/Workspace.PNG](./media/Eclipse/1.PNG)  

Escollim un Projecte General  

![./media/Eclipse/Workspace.PNG](./media/Eclipse/2.PNG)   

Aqui posarem el nom del projecte a definir (posarem el mateix que la futura pàgina web) 

![./media/Eclipse/Workspace.PNG](./media/Eclipse/3.PNG)  

  

### 6.Definició de Repositori local  

Per definir el repositori local primer farem buscarem la pestanya marcada a la imatge:  


![./media/Eclipse/Workspace.PNG](./media/Eclipse/git_pas1.PNG)  

Farem click al contenidor + per crear un nou  

![./media/Eclipse/Workspace.PNG](./media/Eclipse/git_pas2.PNG)  

  

escollim el nom del projecte en questió   

![./media/Eclipse/Workspace.PNG](./media/Eclipse/git_pas3.PNG)  

Comprovem com ha funcionat:  

![./media/Eclipse/Workspace.PNG](./media/Eclipse/git_pas4.PNG)  

![./media/Eclipse/Workspace.PNG](./media/Eclipse/git_pas5.PNG)  

important esborrar l'arxiu per defecte que ens crea el Git ja que no ens interessa un nou projecte fet per Git  

![./media/Eclipse/Workspace.PNG](./media/Eclipse/git_pas6_ignore.PNG)   
  

  


### 7.Creació de Repositori de GitHub

![./media/Eclipse/Workspace.PNG](./media/GitHub/1.PNG)  

Creem el nou repositori al GitHub amb el nom del nostre projecte local  

![./media/Eclipse/Workspace.PNG](./media/GitHub/2.PNG)  

i copiem la direcció URI per després poder-ho pujar del nostre projecte local al projecte GitHub

   

![./media/Eclipse/Workspace.PNG](./media/GitHub/3.PNG)   



 

   


### 8.Exportació de la branca "master" local sobre repositori GitHub  

En el nostre repositori local fem un Push a la branca principal (ja que no tenim cap branca secundaria)

![./media/Eclipse/Workspace.PNG](./media/GitHub/4.PNG)  

enganxem la nostra URI (CTRL + V)   

![./media/Eclipse/Workspace.PNG](./media/GitHub/5.PNG)  

Rèplica feta!!!   

![./media/Eclipse/Workspace.PNG](./media/GitHub/6.PNG)   
