Raccolta dei file .css e degli script utilizzati per [*DropSea*](https://dropseaofulaula.blogspot.com/) e [*ScienceBackstage*](https://sciencebackstage.blogspot.com/) e gli altri miei blog. Tutti i link per l'incorporazione sono generati con [jsDelivr](https://www.jsdelivr.com/)

* Stile per il blog *DropSea*: [*link* da usare per l'incorporazione](https://cdn.jsdelivr.net/gh/ulaulaman/dropsea@codice_commit/dropsea_styles.css)

Gli altri css sono
* [dropsea.css](css/dropsea.css) - Il *css* con tutte le personalizzazioni rispetto al tema
* [table.css](css/table.css) - Incorporato in [*DropSea*](dropsea_styles.css)
* [libro.css](css/libro.css) - Incorporato in [*DropSea*](dropsea_styles.css)
* [planet.css](css/planet.css) - Usato in [*ScienceBackstage*](https://sciencebackstage.blogspot.com/)

## Schede libri (e recensioni)

Definito uno [schema css](https://github.com/ulaulaman/dropsea/blob/master/css/libro.css) per i libri e le recensioni:

**Esempio**:

&lt;scheda&gt;&lt;titolo&gt;DropSea&lt;/titolo&gt;&lt;autore>Gianluigi Filippelli&lt;/autore>&lt;trad>Un traduttore&lt;/trad>&lt;ed>Me stesso&lt;uscita>2002&lt;/uscita>&lt;/ed>&lt;formato>&lt;pag>3000&lt;/pag>brossurato&lt;euro>10&lt;/euro>&lt;/formato>&lt;isbn>isbn&lt;/isbn>&lt;/scheda>

In alternativa a &lt;euro> si possono usare anche le *tag* &lt;dollaro> e &lt;lira>