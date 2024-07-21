## grid track is space between 2 grid lines
## grid area is area between 2 horizontal and 2 vertical lines
## grid-template-columns :kitne columns bnege kitne size ke
## grid-template-rows :kitne rows bnegi kitni size ki
## grid lines can be named
## change posiytion of any grid box by:
1.grid-row=1/2 (line no. 1 se lekar line no.2 tk)
2.grid-column=1/2(line no. 1 se leekar 2 tk)
##          or
1.grid-row-start:
2.grid-row-end:
3.grid-column-end:
4.grid-column-start:

### 2nd way to form grid:
1.grid-template-area:"" "" "";
2.grid-area:

## units:
1fr: available width ka 1 fraction

## gap->gap between columns and rows
## row-gap-> gap between rows
# column-gap-> gap between columns

## align-items:
## justify-items:

### ek cell pr lagti hain
## align-self:
## justify-self:

## agr grid-container bada hai aur grid choti then we use 
## justify-content:
## align-content:
## place-content is for both justify-content and align-content

## repeat function
## repeat(4,1fr)--> repeat 1 fr 4 times
## repeat(4,minmax(100px,1fr))--> minimum 1100px hogi and maximium 1 fr hogi