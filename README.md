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
