> [!WARNING]
> This readme will be in Catalan instead of English

# WEBCV
## CV en forma de web estàtica per a l'assignatura de Multimèdia i Interfícies d'Usurari

## Taula de continguts
- [User Persona](#user-persona)
- [Informació d'arquitectura](#informació-darquitectura)
- [Disseny visual](#disseny-visual)
- [Projecte de Figma i altres afers](#altres)


>## User Persona
Nom: Laura, 37 anys
Professió: RRHH en una empresa de tecnologia (Recruiter)
Objectius: La Laura vol veure un CV clarament estructurat i fàcil de llegir, amb una secció d'experiència laboral per poder veure si encaixes a l'empresa i el teu potencial.
Comportament: Laura revisa el lloc web ràpidament, cercant informació específica com la formació i les habilitats, i li agrada veure certa experiència en llocs del sector per poder fer una cerca més acotada de treballadors.
Frustracions: Si la pàgina és desordenada o difícil de navegar, Laura podria perdre interès i no continuar explorant.

>## Informació d'Arquitectura

En aquest projecte he dissenyat i implementat una pàgina web per al meu CV en línia, dividint la pàgina en diverses capes per organitzar la informació i millorar l'experiència d'usuari.

## 1. Capes de la Pàgina Web

### 1.1 Head
El **head** conté els metadades bàsiques per a la pàgina web:
- Metadades comunes per a SEO i accessibilitat.
- Icona personalitzada per a la pàgina.
- Referència al document **CSS** per a l'estil de la pàgina.
- Títol de la pàgina web, que apareix a la pestanya del navegador.

### 1.2 Body
El **body** és el contingut visible de la pàgina, i està organitzat en 5 blocs diferenciables:

#### 1.2.1 Títol
Conté el **títol** principal i el **subtítol** de la web, que són els primers elements visibles per a l'usuari. Aquest conjunt de text està format per dos **divs** que agrupen el contingut i ajuden a crear un impacte visual immediat.

#### 1.2.2 Experiència Laboral
Aquest apartat mostra la meva **experiència laboral**:
- Cada experiència laboral està dividida en un **div** separador.
- S'ha creat una biblioteca de fotos per mostrar projectes visuals o experiències professionals.
- Els **divs** estan organitzats mitjançant **flexbox** per gestionar l'espai entre ells i crear una disposició neta i adaptativa.

#### 1.2.3 Educació
Aquesta secció mostra la meva formació acadèmica, incloent títols i institucions educatives.

#### 1.2.4 Habilitats Addicionals
Aquesta secció destaca altres **habilitats rellevants** en el meu perfil professional, com coneixements en tecnologies i eines.

#### 1.2.5 Contacte (Footer)
El **footer** conté les meves dades de contacte, presentades com a **enllaços**:
- Adreça de correu electrònic.
- Xarxes socials o altres canals de comunicació.

## Raonament
Aquesta arquitectura ha estat dissenyada per garantir una navegació fluida i un disseny net, amb un enfocament en la visualització d'informació important des del primer moment. Cada secció està separada i estructurada per facilitar la lectura i l'accessibilitat.





>## Disseny Visual

He près varies decisions de disseny per fer el meu projecte més entenedor, bonic i professional.

## 1. Fonts
> [!NOTE]
> Les fonts descrites a continuació són adjuntes al projecte, cal tenir.les a l'ordinador per veure-ho en local

#### 1.1 Randall  He optat per fer ús de la font **Randall**. És una font voluminosa i visual, però no és gens pesada, és molt agradable a la vista i té personalitat. L ahe triat per a títols i apartats, de manera que es mostra un ènfasi en aquests.
#### 1.2 Just Sans  Per al text bàsic he usat **Just Sans**. La he triat ja que volia una font sense serifa ja que en documents web és més agradable. A més a més és més formal que altres sans.

## 2. Paleta de colors
> [!NOTE]
> No incloc el codi de la paleta de colors ja que no es pot visualitzar

He fet ús d'un apaleta de colors molt agrtadable del tipus "pastel" i "café". Són colors que no generen fatiga visual i són agradables de llegir (a diferència de colors més vius o clars que a la llarga desgasten la vista)

## 3.  Separacions
He afegit prous separacions per tal que es vegi una pàgina ordenada i no sembli saturada. El text combina amb la vora i no es sent apretat en cap moment.

## 4.  Galeria d'imatges
He creat una galeria d'imatges simple però molt visual dels llocs de treball que he tingut. Al passar el cursor per sobre es fa ènfasi en la imatge actualamb un atransició.



>##  Altres

El link al projecte de Figma és el seguent: (https://www.figma.com/design/VavAo7VEdJXWLuuFTfPBM0/WEBCV?node-id=0-1&t=fM8mKuFxcjViVnFu-1)

He aprés tant com gaudit fent aquest projecte. Una cosa era veure la teoria i una altra molt diferent és posar-ho a prova en un projecte així. M'han anat sorgint problemes però poc a poc els he anat solucionant. 
> [!NOTE]
> Inicialment volia fer que el text **CONTACTE** sortis de sota el footer al passar el cursor per sobre, però no me n'he ensortit.


