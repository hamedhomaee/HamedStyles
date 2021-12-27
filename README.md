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
  * display-flex-row
  * display-flex-row-reverse
  * display-flex-column
  * display-flex-column-reverse
  * display-block
  * display-inline
  * display-inline-block 
  * display-none 
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
* For flex displays following justify self are provided ([size]-[justify-self])
  * justify-self-end
  * justify-self-start
  * justify-self-center
  * justify-self-stretch
  * justify-self-baseline
* For flex displays following align self are provided ([size]-[align-self])
  * align-self-center
  * align-self-start
  * align-self-end
  * align-self-stretch
* For flex displays, to set flex-wrap to "wrap" ([size]-[flex-wrap])
  * flex-wrap
* For flex displays, to disable flex-shrink (by default it is enabled) ([size]-[flex-shrink])
  * flex-shrink-disable
* For flex displays, to enable flex-grow (by default it is disabled) ([size]-[flex-grow])
  * flex-grow-enable
* Text decoration none for any size, this class should be given to the parent, whose anchor tags should have no text decoration ([size]-[text-decoration-none])
  * text-decoration-none
* Following text alignment are provided ([size]-[text-alignment])
  * text-align-start
  * text-align-end
  * text-align-left
  * text-align-right
  * text-align-center
  * text-align-justify
  * text-align-justify-all
  * text-align-match-parent
* Following options for <b>textarea</b> element is available ([size]-[resize])
  * resize-none
  * resize-both
  * resize-horizontal
  * resize-vertical
  * resize-block
  * resize-inline
### Some useful pre-made items are available here, which can be easily customized. <b>Note:</b> styles like padding, border, etc should be set manually, since they are very versatile.
* Form with two elements at each row and one row with content at center
```
<div class="s1-width-10 s1-display-flex-column">
    <div class="s1-width-100 s1-display-flex-row s1-justify-content-start s1-align-items-center">
        <div class="s1-width-30">Label</div>
        <div class="s1-width-70">
            <input type="text" class="s1-width-100">
        </div>
    </div>
    <div class="s1-width-100 s1-display-flex-row s1-justify-content-center s1-align-items-center">
          <input type="submit" value="send">
    </div>
</div>
```