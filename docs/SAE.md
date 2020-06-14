## 12 SAE

<br/>

>  Grup: Sistemes Tramviaris · Número elements: 1

<br/>

Sistema d'Ajut a l'Explotació. És el sistema que permet ubicar els tramvies, ajuda en la gestió d'horaris i permet assignar serveis i agents de conducció a un tramvia determinat.

<br/>

### 001 Etiquetes

> `Identificador: 12001 | Codi: SAE | Geometria: PUNT`

<br/>

Punts d'etiqueta que formen part del SAE (sistema d'ajut a l'explotació). Element de la via que permet corregir la posició del tramvia per al SAE. Una vegada el tramvia ha passat per sobre un d'aquests elements la posició es calcula via hodòmetre embarcat, dispositiu que pot arrossegar cert error. Aquest error és corregit cada vegada que un tramvia fa lectura d'una etiqueta.

<br/>

<center>![120011](img/120011.jpg)</center>

<br/>

**Atributs**

| Atribut       | Tipus    | Descripció  |
| ------------- |:-------------| :-----|
| XARXA         | Indica a la xarxa a la qual pertany la infraestructura tramviària. Actualment Trambaix (TBX) o bé Trambesòs (TBS). En un futur es podran incloure altres xarxes encara no definides. | [String (20)] |
| CODI_ACTIU    | Codi que identifica un element en el GIS de forma unívoca. Està format per 4 parts separades per un guió. Comença amb el prefix TRM, després el codi de l'element segons el model de dades, un numero de dos dígits que indica l'operador o creador i un número de 5 dígits que identifica l'element al GIS de forma única.      |   [String (20)] |
| VIA | Determina sobre quin número de via es troba l'element. Els números de via són 1, 2, 3 i 4. | [String (20)] |
| CODI_SISTEMA_SAE | Codi intern de l'etiqueta del sistema SAE. | [String (20)] |


<br/>

**Representació GIS:**

<br/>
<center>![120012](img/120012.jpg)</center>
<br/>

    Nom capa element: Sae-etiquetes
    Nom taula DB: atmgis_12_etiquetes
    Nom camp geometria DB: geom
    Representació gràfica:

        [symbol: 'etiqueta_sae_v3.svg', angle: '180', size: '3', weight: '0.4', color: '#04925e', fillcolor: '#d9fdf1']
