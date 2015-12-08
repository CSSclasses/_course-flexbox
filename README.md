# Flexbox Course

* [Introduction]()
* [display: flex]()
* [flex-direction]()
  * [row]()
  * [column]()
* [order]()
* [justify-content](#justify-content)
  * [flex-start]()
  * [flex-end]()
  * [center]()
  * [space-between]()
  * [space-around]()
  * [inherit]()
  * [initial]()
  * [unset]()
* [align-items]()
  * [flex-start]()
  * [flex-end]()
  * [center]()
  * [baseline]()
  * [stretch]()
  * [inherit]()


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

* http://flexboxfroggy.com
* [What the Flexbox!?](https://www.youtube.com/playlist?list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid)
