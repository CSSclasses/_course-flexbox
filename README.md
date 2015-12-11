# Flexbox Course

Explanation Flex container and flex children, main-axis & cross-axis.

* Introduction
* [display: flex](#display--flex)
* [flex-direction]()
  * [row]()
  * [column]()
* [order]()
* [justify-content](#justify-content)
  * [flex-start](#flex-start)
  * [flex-end](#flex-end)
  * [center](#center)
  * [space-between](#space-between)
  * [space-around](#pace-around)
* [align-items](#align-items)
  * [flex-start](#flex-start-1)
  * [flex-end](#flex-end-1)
  * [center](#center-1)
  * [baseline](#baseline)
  * [stretch](#strecht)

## display – Flex
`display: flex;` defines a flex container. This enables a flex context for all its direct children (`.flex-container > .flex-child`).
```
.flex-container {
  display: flex; /* inline-flex */
}
```

## flex-direction
The flex-direction CSS property specifies how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).
```
flex-direction: row;
flex-direction: row-reverse;
flex-direction: column;
flex-direction: column-reverse;
```

### flex-direction: row
#### row
The flex container's main-axis is defined to be the same as the text direction. The main-start and main-end points are the same as the content direction.

#### row-reverse
Behaves the same as row but the main-start and main-end points are permuted.

### flex-direction: column
#### column
The flex container's main-axis is the same as the block-axis. The main-start and main-end points are the same as the before and after points of the writing-mode.

#### column-reverse
Behaves the same as column but the main-start and main-end are permuted.

## justify-content
### flex-start
The flex items are packed starting from the main-start. Margins of the first flex item is flushed with the main-start edge of the line and each following flex item is flushed with the preceding.

### flex-end
The flex items are packed starting from the main-end. The margin edge of the last flex item is flushed with the main-end edge of the line and each preceding flex item is flushed with the following.

### center
The flex items are packed toward the center of the line. The flex items are flushed with each other and aligned in the center of the line. Space between the main-start edge of the line and first item and between main-end and the last item of the line is the same.

### space-between
Flex items are evenly distributed along the line. The spacing is done such as the space between two adjacent items is the same. Main-start edge and main-end edge are flushed with respectively first and last flex item edges.

### space-around
Flex items are evenly distributed so that the space between two adjacent items is the same. The empty space before the first and after the last items equals half of the space between two adjacent items.

## align-items
### flex-start
The cross-start margin edge of the flex item is flushed with the cross-start edge of the line.

### flex-end
The cross-end margin edge of the flex item is flushed with the cross-end edge of the line.

### center
The flex item's margin box is centered within the line on the cross-axis. If the cross-size of the item is larger than the flex container, it will overflow equally in both directions.

### baseline
All flex items are aligned such that their baselines align. The item with the largest distance between its cross-start margin edge and its baseline is flushed with the cross-start edge of the line.

### stretch
Flex items are stretched such as the cross-size of the item's margin box is the same as the line while respecting width and height constraints.

## Global values both justify-content & align-items
* align-items: inherit;
* align-items: initial;
* align-items: unset;

## Resources
* [http://flexboxfroggy.com](http://flexboxfroggy.com)
* [What the Flexbox!?](https://www.youtube.com/playlist?list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid)
* [Solved by Flexbox](https://philipwalton.github.io/solved-by-flexbox/)
* [Flexbugs](https://github.com/philipwalton/flexbugs)
* [Zoe Gillenwater – Enhancing Responsiveness with Flexbox](https://www.youtube.com/watch?v=_98SE8WUvLk&list=PL37ZVnwpeshHoV6GgvG9WWAP6rjnEdAs9)
* [A complete guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [MDN – Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes)
* [Learn Layout - Flexbox](http://learnlayout.com/flexbox.html)
* [Can I Use](http://caniuse.com/#feat=flexbox)
* [Smashing Magazin article – Flexbox](http://www.smashingmagazine.com/2013/05/centering-elements-with-flexbox/)
