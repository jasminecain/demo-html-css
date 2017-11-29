# HTML and CSS - oh the places you will go

### Start general and build up

Structure
Content
Styling

## The witches page uses Flexbox

Notes:

Everything outside a flex container and inside a flex item is rendered as usual.
The flex container is declared by setting the display property of an element to either flex (rendered as a block) or inline-flex (rendered as inline).
Lined up with the flex line.

###More
Change the direction content flows
```bash
direction: rtl;
```

Change the direction of the flexible items inside the flex container
```bash
flex-direction: row;
flex-direction: row-reverse;
flex-direction: column
flex-direction: column-reverse
```

justify-content property horizontally aligns the flexible container's items when the items do not use all available space on the main-axis.
```bash
-webkit-justify-content: flex-end;
justify-content: flex-end;

flex-start - Default value. Items are positioned at the beginning of the container
flex-end - Items are positioned at the end of the container
center - Items are positioned at the center of the container
space-between - Items are positioned with space between the lines
space-around - Items are positioned with space before, between, and after the lines
```
