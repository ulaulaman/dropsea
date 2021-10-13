Raccolta dei file .css e degli script utilizzati per [*DropSea*](https://dropseaofulaula.blogspot.com/), [*Doc Madhattan*](http://docmadhattan.fieldofscience.com/) e [*ScienceBackstage*](https://sciencebackstage.blogspot.com/) e gli altri miei blog. Tutti i link per l'incorporazione sono generati con [jsDelivr](https://www.jsdelivr.com/)

* Stile per il blog *DropSea*: [*link* da usare per l'incorporazione](https://cdn.jsdelivr.net/gh/ulaulaman/dropsea@codice_commit/dropsea.css)
* Stile per il blog *Doc Madhattan*: [*link* da usare per l'incorporazione](https://cdn.jsdelivr.net/gh/ulaulaman/dropsea@codice_commit/docmad.css)

Gli altri *css* sono
* [drop.css](css/drop.css) - Il *css* con le personalizzazioni specifiche di *DropSea*. Incorporato in [*DropSea*](dropsea.css)
* [table.css](css/table.css) - Definisce una tabella personalizzata. Incorporato in [*DropSea*](dropsea.css) e [*Doc Madhattan*](docmad.css)
* [libro.css](css/libro.css) - Definisce la scheda dei libri. Incorporato in [*DropSea*](dropsea.css)
* [boxes.css](css/boxes.css) - Definisce varie personalizzazioni relative a contenitori e immagini. Incorporato in [*DropSea*](dropsea.css) e [*Doc Madhattan*](docmad.css)
* [doc.css](css/doc.css) - Il *css* con le personalizzazioni specifiche di *Doc Madhattan*. Incorporato in [*Doc Madhattan*](docmad.css)
* [planet.css](css/planet.css) - Usato in [*ScienceBackstage*](https://sciencebackstage.blogspot.com/)

## Schede libri (e recensioni)

Definito uno [schema *css*](https://github.com/ulaulaman/dropsea/blob/master/css/libro.css) per i libri e le recensioni:

**Esempio**:

&lt;scheda&gt;&lt;titolo&gt;DropSea&lt;/titolo&gt;&lt;autore>Gianluigi Filippelli&lt;/autore>&lt;trad>Un traduttore&lt;/trad>&lt;ed>Me stesso&lt;uscita>2002&lt;/uscita>&lt;/ed>&lt;formato>&lt;pag>3000&lt;/pag>brossurato&lt;euro>10&lt;/euro>&lt;/formato>&lt;isbn>isbn&lt;/isbn>&lt;/scheda>

In alternativa a &lt;euro> si possono usare anche le *tag* &lt;dollaro> e &lt;lira>