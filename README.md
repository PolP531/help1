# Help Commands

## 1- Comandes essencials per pujar un arxiu a GitHub: 

1- Serveix per clonar un repositori del GitHub a carpeta local de l'ordinador.

<pre>git clone <link del repositori> </pre>

2- Si no tenim un readme i volem crear-lo desde GitBash, fem la seguent comanda: 
<pre> git add readme.md </pre>

3- Quan ja tenim fet el document i hem posat la informació que volem, posem el seguent per actualitzar el document per afegir les actualitzacions al arxiu: 

<pre>git add <nom arixu> </pre>

Fet això, afegim els canvis amb el "Commit", on posarem un titol per posar un "Parche" en el nostre document
<pre>git commit -m "nom" </pre>

Per acabar de pujar el arxiu, em de "empuxar" el arxiu dins del GitHub amb la seguent comanda: 
<pre>git push -u origin main </pre>

A més a més, si volem anar veient el estat del GitHub o del arxiu, podem fer servir això:
<pre>git status </pre>

## 2- Apunts Markdown

1- Mides de capçalera: 
    Per fer capçaleres farem servir el #, com més # posem, més petita serà: 

<pre> # La capçalera més gran equival a <H1> d'HTML
## La segona capçalera més gran equival a <H2> d'HTML
### La tercera capçalera més gran equival a <H3> d'HTML
#### La quarta capçalera més gran equival a <H4> d'HTML
##### La segona capçalera més petita equival a <H5> d'HTML
###### La capçalera més petita equival a <H6> d'HTML  </pre>

2- **Negreta:** 
    Per fer servir la negreta farem servir el <pre>** ** </pre>

<pre> **Aquest text està en negreta** </pre>

3- *Cursiva* 
    Es fa el mateix que en negreta pero amb només un <pre>* * </pre>
<pre>*Aquest text està en cursiva* </pre>

4- ~~Ratllat ~~ 
    Per rallar-lo, hem de posar <pre> ~~ ~~ </pre>
~~Aquest text està rallat~~

5- Citar Text: 
    Per citar farem servir <pre> > </pre>

    Com va dir el mariner 
    > Más vale trava linda que mina fea 


