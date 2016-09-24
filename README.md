https://github.com/hmteditors/leiden/README.md

**This is the working directory of the Leiden sub-group of the Homer Multitext Project.**

#Leiden

Editing HMT material at Leiden University

- *Iliad* 13 in the Venetus A:  folios 164 recto - 169 recto (inclusive)
- http://homermultitext.github.io/hmt-docs/totaled/

**Basic infrastructure for working with digital representations of manuscripts**
- creating a model of the page sequences of Leiden University, codex VGF 64
- creating a navigational index of Iliad lines in VGF 64

##Table of contents

- What is there on a folio? 
- What ought to be done to complete a folio?
- Which files ought to be edited?
- Useful links for editing
- Progress

##What is there on a folio?

* The main text of the *Iliad*
* Main scholia
* Intermarginal (**im**) scholia (between the main text and the main scholia)
* Interlinear (**il**) scholia (between the lines of the main text)
* Interior (**int**) scholia (in the inner margin of the folio, *i.e.* to the left of the main text on *recto* pages and to the right of the main text on *verso* pages)
* Exterior (**ext**) scholia (in the outer margin of the folio, *i.e.* to the right of the main scholia on *recto* pages and to the left of the main scholia on *verso* pages)
* Special signs, numbers, and abbreviations (these can be ignored for now, because this is done systematically by someone else)

**NB**: not all folios have all types of scholia

##What ought to be done to complete a folio?

* Make a palaeographic sample of every glyph in the first line of the main text on each folio (`csv`)
* Index the individual lines of the main text (`csv`)
* Index the individual main, *im*, *il*, *int*, and *ext* scholia (`csv`)
* Transcribe the individual lines of the main text (`xml`)
* Transcribe the individual main, *im*, *il*, *int*, and *ext* scholia (`xml`)

##Which files ought to be edited?

* `collections/paleography{folio}.csv`
* `indices/venA-textToImage-Iliad.csv`
* `collections/venA-mainScholia{folio}.csv`
* `collections/venA-intermarginal{folio}.csv`
* `collections/venA-interlinear{folio}.csv`
* `collections/venA-interior{folio}.csv`
* `collections/venA-exterior{folio}.csv`
* `editions/Iliad/{folio}.xml`
* `editions/scholia/MainScholia{folio}.xml`
* `editions/scholia/IntermarginalScholia{folio}.xml`
* `editions/scholia/InterlinearScholia{folio}.xml`
* `editions/scholia/InteriorScholia{folio}.xml`
* `editions/scholia/ExteriorScholia{folio}.xml`

##Useful links for editing

* http://www.homermultitext.org/hmt-digital/svcforms (to search for images of a folio. It is recommended to have the Venetus A and the Comparetti open in adjacent tabs)
* http://homermultitext.github.io/hmt-editors-guide/editorial-policies/ (to look up the HMT `xml` editing standards)
* https://homermultitext.slack.com (to contact Neel or Stephanie)

##Progress

<table>
  <tr>
    <td> </td>
    <td>` 164r, 164v, 165r, 165v, 166r, 166v, 167r, 167v, 168r, 168v, 169r`
  </tr>
  <tr>
    <td>paleography (`csv`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>main text indices (`csv`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>main scholia indices (`csv`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>intermarginal scholia indices (`csv`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>interlinear scholia indices (`csv`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>interior scholia indices (`csv`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>exterior scholia indices (`csv`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td> </td>
    <td>` 164r, 164v, 165r, 165v, 166r, 166v, 167r, 167v, 168r, 168v, 169r`
  </tr>
  <tr>
    <td>main text (`xml`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>main scholia (`xml`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>intermarginal scholia (`xml`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>interlinear scholia (`xml`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>interior scholia (`xml`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
  <tr>
    <td>exterior scholia (`xml`)</td>
    <td>`  y  |  y  |  y  |  y  |  ?  |  ?  |  ?  |  ?  |  ?  |     |     `
  </tr>
</table>

**NB**: *y*: yes, finished; *?*: unclear
