## 19 Estructures complemetàries

<br/>

>  Grup: Sistemes Auxiliars · Número elements: 1

<br/>

La categoria d'estructures complementàries fa referència a aquelles estructures, ja siguin executades amb les obres del tramvia o a posteriori en fase d'explotació, que estan presents o són molt properes a l'àmbit del domini públic tramviari i que tenen o poden tenir alguna interrelació amb el servei o amb l'estat de conservació i manteniment de la infraestructura tramviària.

<br/>

### 001 Estructura

> `Identificador: 19001 | Codi: EST | Geometria: POLÍGON`

<br/>

Estructures d'obra singulars integrades dins o a prop de la plataforma del tramvia. Es tracta d'estructures (ponts, passos inferiors, murs, etc.) modificats o executats durant les obres de realització del tramvia o ja en fase d'explotació.

<br/>

<center>![190011](img/190011.jpg)</center>

<br/>


**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| TIPUS | Indica el tipus d'estructura complementària de la que es tracta. Pot tractar-se de ponts, de passos soterrats o de murs. L'atribut ha de tenir un dels següents valors:<li>**Pont**:Estructura complementària de tipus pont.</li><li>**Pas soterrat**:Estructura complementària de tipus pas soterrat.</li><li>**Murs**:Estructura complementària de tipus mur.</li><li>**Intercanviador**:Estructura complementària de tipus intercanviador.</li><li>**Respiradell**:Estructura complementària de tipus respiradell.</li> | [String (20)] |
| DOCUMENT_ASSOCIAT | Camp amb la URL del document que conté informació de l'estructura. | [String (500)] |



<br/>

**Representació GIS:**

<br/>
<center>![190012](img/190012.jpg)</center>
<br/>

    Nom capa element: Estructures complementàries-estructura
    Nom taula DB: atmgis_19_estructura
    Nom camp geometria DB: geom
    Representació gràfica:

        [weight: '0.26', dasharray: 'continua', color: '#1f78b4', fillcolor: '#46f8f3', fillstyle: 'trama densa']
