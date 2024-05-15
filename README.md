# LLEGIU-ME
Un repositori per publicar la meva primera pàgina web. Aquesta pàgina web es troba publicada a [GRADOT](https://albertroviraduch.github.io/GRADOT/).

## Tema i motivació
En el marc de l'assignatura de Eines Web, Producció i disseny cartogràfic s'ha tingut que elaborar una pàgina web per tal de complir els obejctius de l'assignatura. La meva pàgina web s'anomena GRADOT (Grup de Recerca d'Anàlisis de Dinàmiques D'ordenació Territorial). He fet la pàgina web d'aquest tema perquè durant el transcurs de la carrera una de les temàtiques que mès m'ha agrdat és la dedicada a temes d'ordenació i desenvolupament territorial focalitzant en la zona del la província de Tarragona ja que és la més propera a aquesta facultat de Turisme i Geografia de la Universitat Rovira Virgili (URV).  

## Dades i continguts
La idea de realitzar GRADOT, bé de prendre de referència el Grup de Recerca GRATET de la URV.
Una imatge d'exemple:
![Un dia al campus de la FTG](./images/imatge-de-prova.jpg "Un dia al campus de la FTG").

D’on s’han tret:

- La inspiració per realitzar ha sigut la pàgina web de GRATET i les dades m'he inspirat en treballs que hem realitzat al llarg del Grau de Geografia, Ànalisi Territorial i Sostenibilitat 
- El text ha sigut inscrit per inspiració própia. 
- Les imatges s'han extret de internet moltes d'elles, per no dir totes. 


## Estructura de la Web. 
L’estructura de l’estructura web, és molt senzilla compta amb 5 grans pàgines: Inici, Membres, Projectes, Mapa i Formulari de Contacte. 

Aquests apartats, juntament amb el titol GRADOT i una imatge de l’universitat Rovira i Virgili, concretament de l'entrada principal de la Facultat de Geografia amb un fons de color gris clar conformen el Header. Aquest Header és repeteix pels 5 aparts. La imatge de la facultat de geografia i turisme si fem click sobre ella ens porta a la pàgina d’inici.  

A baix de tot de cada apartat he posat un peu de pàgina o footer amb fotos del logo de les principals xarxes socials i si fem click ens porta a la pàgina d’inici d’aquestes xarxes. També he col·locat un boto que s'anomena Torna a l'inici que si clickem sobre ell ens retorna al capdavant de la pàgina. 

Entre mig del footer i header, hi ha el body o cos, cada apartat te un layout diferent per tal de no fer simple i senzilla el portal web. A continuació explicare el layout d’una manera ràpida com són
  - Inici: Text de color negre amb margin i padding per tal de facilitar millor la lectura i no quedi apretat al final i inici de la pàgina web. També he afegit amb comandament HTML els punts de color negre per       tal de fer una ennumeraciño i ficar de manera més gràfica la pàgina web.
  - Membres: Text de color negre amb els H1 i H2 remarcats amb negreta per tal de donar-li més importància i dinamisme. S’articuula amb 3 columnes de 2 files amb les línies  transparents, és a dir amb una             opacitat del 100% i amb imatges per cada membre amb una breu explicació a baix de cada imatge sobre el càrrec o funció dins del grup. Al capdamunt del body he redactat de manera breu i en punts com a l’inici      l’introducció del equip investigador. Cada membre és troba a dintre de unes w3-card. 
  - Projectes: Text de color negre menys els links dels projectes anteriors, que els hi resaltat per tal de donar i captar visibilitat. Aquest apartat s’estrctura amb 3 subapartats (Projectes anteriors, projectes     actuals i projectes futurs) aquests títols estan remarcats amb negreta. Pel que fa els projectes anteriors primer he posat una línia d’explicació i després 3 projectes realitzats amb un link que t’emporta a       aquests projectes, época de realització del projecte i els membres que han realitzat el projecte concret. El interliniat que he fet servir, és diferent a la resta per tal de que quedi ordenat i coherent. El       projecte en curs, he optat per ficar un llistat amb punts
  - Mapa: A l’entrega de l’esborrany s’ha realitzat un mapa LEAFLET amb JavaScript.Primer de tot trobem el títol remarcat de color negreta i centrat al mig del site web.  A baix del títol una molt breu explicació     de com interpretar el mapa. El mapa, ha estat afegit a través del complement Leaflet amb Java Script i el mapa de fons és un open street map amb 3 punts de collor blau i 3 de color verd. Els punts                 representen el context geogràfic d’on he realitatzat els projectes, els blaus dels anteriors i el verds dels actuals. Aquest mapa al clickar sobre els punts t’indica el municipi del àmbit del prjecte i            també et permet fer més o ments zoom al mapa. El mapa, ocupa tota la pàgina web per  tant no hi ha margin.

    A mesura que vam avançar en les classes magistrals, el mapa realitzat amb Java Script i Leaflet s'ha esborrat i s'ha realitzat un amb el QgisWeb personalitzat, que més abaix a l'apartat de cartografia explico     com s'ha fet. 
  - Formulari de Contacte: En aquest apartat trobem el titol i el formulari centrat al mig de la pàgina. L’he configurat de manera que resulti obligatori els camps menys el missatge. 


## Web responsive
Per tal d’ajudar i facilitar la comprensió en totes les pantalles s’ha aplicat un responsive per els 3 tamanys de dimensió de dispositius. A continuació a l’imatge 4, podem veure el responsive aplicat. Per l'aplicació del responsive s'han utilitzat @media queries. 
Per les pantalles mitjanes i grans i ficat un minim en canvi per les petites no. 

![RESPONSIVE](https://github.com/AlbertRoviraDuch/test/assets/168575868/d9106258-308e-44d7-bc81-58747eb4b552)

## Cartografia
Cóm s’han integrat i elaborat els mapes que apareixen a la web.

## Dificultats/millores
Reflexiona proactivament sobre el producte elaborat.

1. Anteriorment a l'assignatura mai he treballat amb ninguna cosa relacionada amb programació llavors al començar m'ha costat adpatar-m'hi al Visual Studio Code,Github, CSS, HTML i Java Script
2. Sòc una persona desdendraçada amb carpetes i fitxers de l'ordenador i m'ha costat manejar el Visual Studio Code amb els diferents apartats
3. Al ser un novat amb la programació hi havia coses que m'hagues agrdat fer i no he pogut perquè els meus coneixemnts de programació són molt bàsics
