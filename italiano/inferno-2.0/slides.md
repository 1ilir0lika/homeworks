---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: images/sfondo.webp
# some information about your slides (markdown enabled)
title: Inferno 2.0
info: |
  E se la divina commedia fosse stata scritta nel 2024?

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# Inferno 2.0
Come sarebbe la divina commedia se fosse stata scritta nel 2024?


<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    scopriamolo subito <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <p>Ilir Lika IVB</p>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-right
image: images/gironi.jpg
---

# I nuovi gironi

<v-clicks depth="2">

- 📝 **I Disinformatori** - coloro che diffondono disinformazione per trarne vantaggio 
  - I truffatori - disinformano per trarre vantaggi economici &rarr; BigLuca
  - I demagoghi - personaggi pubblici che dissuadono il popolo con la parola &rarr; Vittorio Feltri
- 💵 **Avidi** - coloro che vogliono lucrare su tutto &rarr; Sam Altman
  <!--
  - 👑 **Macchiavellisti** - coloro che mettono i loro obbiettivi davanti a tutti senza curarsi dell'impatto che avranno sul mondo 
  -->
</v-clicks>




<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---

# Gli avidi


|     |     |
| --- | --- |
| il peccato | persone facoltose che non per necessitá,quanto piú per sfizio personale,cercano di **lucrare in ogni occasione possibile** 
| la pena per contrappasso | devono continuamente portare al di sopra di una montagna dei lingotti d'oro,il problema é che questi al raggiungere della cima scivolano e quindi devono ripeterlo eternamente,cercano di arricchirsi,ma la loro insaziabilitá non li fa mai bastare ció che hanno |
| i peccatori | sono superbi e credono di essere al di sopra di Dio e di questa pena,ma nonostante la loro insubordinazione sono obbligati a svolgere la pena |
| il girone | il girone consiste solamente in un'alta montagna accerchiata dai dannati|

---
layout: image-right
image: images/sam.webp
backgroundSize: contain
---

# I dannati

### Sam Altman

ha reso un progetto open e no profit &rarr; openai \
il quale scopo era unicamente la ricerca e la divulgazione di quest'ultima un azienda per trarre profitto

---
transition: slide-up
level: 2
---

# I Disinformatori - i truffatori
## scheda riassuntiva:

|     |     |
| --- | --- |
| il peccato | Diffondere disinformazione al fine di trarre vantaggi economici <span v-mark.red="1">a discapito di altri</span> che si impoveriscono per colpa loro| 
| la pena per contrappasso | spogliati di tutti i loro averi,letteralmente,che fanno a lotta tra di lro per sempre per prendere una banconota |
| i peccatori | si sentono a disagio perché spogliati delle loro ricchezze,che era la loro identitá,ma restano comunque aggressivi tra di loro pur di poter prendere la banconota |
| il girone | Dante prima di entrarci pensava d'aver raggiunto il paradiso,perché da fuori ricordava quello,peró entrando scopre che quella era tutta un'illusione,trovandosi in un posto colmo di oggetti appariscenti,come ad esempio orologi,ma che quando i dannati provavano ad indossare questi delle lesioni su di loro |

---
layout: two-cols
---

# I dannati

### Charles Ponzi
<p>&nbsp;&nbsp;&nbsp</p>

<Transform :scale="0.5">
<img src="/images/charles.jpg"/> 
</Transform>



::right::

<p>&nbsp;&nbsp;&nbsp</p>

### Big Luca 
<p>&nbsp;&nbsp;&nbsp</p>

<Transform :scale="1.3">
<Youtube id="uBRDZLt34l8" />
</Transform>

---

# I Disinformatori - I demagoghi


|     |     |
| --- | --- |
| il peccato | Diffondere disinformazione al fine di <span v-mark.red="1">diffondere violenza ed odio</span>
| la pena per contrappasso | Con la bocca cucita son destinati a far propaganda per sempre,questo comporta un enorme dolore,inoltre queste menzogne prendono luogo fisicamente mutando in una nebbia nera che li avvolge |
| i peccatori | si sentono a disagio perché spogliati delle loro ricchezze,che era la loro identitá,ma restano comunque aggressivi tra di loro pur di poter prendere la banconota |
| il girone | il girone é avvolto interamente dalle menzogne,rappresentate da una nube nera,dette dai dannati,proprio perché queste distolgono la realtá rendendola difficile da afferrare e comprendere|

---
layout: two-cols
---

# I dannati


<Transform :scale="1.3">
<Youtube id="ehkFePMVvZg" /> 
</Transform>

<p>&nbsp;&nbsp;&nbsp</p>
<p>&nbsp;&nbsp;&nbsp</p>
Mario Giordano

Mario Giordano (Alessandria, 19 giugno 1966) è un giornalista, conduttore televisivo e saggista italiano.
Laureato in Scienze politiche presso l'Università degli Studi di Torino, inizia la sua carriera a Il nostro tempo, settimanale cattolico di Torino
::right::

<p>&nbsp;&nbsp;&nbsp</p>

<Transform :scale="1">
<img src="/images/vittorio.jpg" />
</Transform>
Vittorio Feltri

Vittorio Feltri (Bergamo, 25 giugno 1943) è un giornalista, saggista, politico e opinionista italiano.

Direttore di vari quotidiani, quali L'Indipendente, L'Europeo ed il Giornale

---
layout: image-right

image: images/capolavoro.jpg

backgroundSize: 25em 90%
---
# Conclusione
grazie per aver ascoltato tutta la spiegazione

per la lettura di questo grande classico contemporaneo\
é consigliato l'acquisto su amazon a [questo link](https://drive.google.com/file/d/1JtcMSePAKn_MSc8ag3liE5DHRv6IK6NY/view?usp=drive_link)

al modico prezzo di 10000 euro

inclusa la guida sul come ho guadagnato 10000 euro vendendo libri su amazon
