# HamedStyles

## A new style sheet framework with following properties:  
  
### The main minified file to use resides in "Css" folder.
  
* Following display sizes with respective acronyms are supported:
  * min-width 1px = s1
  * min-width 540px = s2
  * min-width 720px = m1
  * min-width 960px = m2
  * min-width 1200px = l1
  * min-width 1400px = l2
  * min-width 1800px = x1
  * min-width 2200px = x2
* Different displays are provided. The size should be prepended ([size]-[display]):
  * display flex row: display-flex-row
  * display flex row reverse: display-flex-row-reverse
  * display flex column: display-flex-column
  * display flex column reverse: display-flex-column-reverse
  * display block: display-block
  * display inline: display-inline
* Different widths in percentage are provided, from 10 to 100% ([size]-[width]); as an example:
  * width 10%: width-10
* Different margins are as follows ([size]-[margin]):
  * margin-right-auto
  * margin-left-auto
  * margin-auto
* For flex displays following justify content options are provided ([size]-[justify-content]):
  * justify-content-end
  * justify-content-start
  * justify-content-center
  * justify-content-space-between
  * justify-content-space-around
  * justify-content-space-evenly
* For flex displays following align items are provided ([size]-[align-items])
  * align-items-baseline
  * align-items-center
  * align-items-flex-start
  * align-items-flex-end
  * align-items-stretch
* Text decoration none for any size, this class should be given to the parent, whose anchor tags should have no text decoration
  * text-decoration-none