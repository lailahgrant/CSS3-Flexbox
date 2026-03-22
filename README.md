# Complete Flexbox Tutorial with a Cheat Sheet - CSS Flex Box
> by **Joy Shahed**

In Flex box, everything is in a **Flex-Container**.
Every item in the **Flex-Container** is a **flex-item**

### Flexbox Architecture
- **Main Axis** is the **X** axis
- **Cross Axis** is the **Y** axis

<img src="./assets/flexbox-architecture.png" alt="CSS Flex box Architecture">

### Flexbox properties
<img src="./assets/flexbox-properties.png" alt="CSS Flex box properties">

### Flexbox chart
<img src="./assets/flexbox-chart.png" alt="CSS Flexbox chart" >

#### Flexbox direction

The Direction / Orientation in wich flex-items are distributed inside **flex-container**.
The Direction can have 4 orientations:
- row
- row-rverse
- column
- column-reverse
The default direction for flex is `row`.

<img src="./assets/flex-direction.png" alt="CSS Flexbox direction" >

- `flex-direction: row;`
<img src="./assets/flex-direction-row.png" alt="flex-direction: row;" >

- `flex-direction: row-reverse;`
<img src="./assets/flex-direction-row-reverse.png" alt="flex-direction: row-reverse;">

- `flex-direction: column;`
<img src="./assets/flex-direction-column.png" alt="flex-direction: column;">

- `flex-direction: column-reverse;`
<img src="./assets/flex-direction-column-reverse.png" alt="flex-direction: column-reverse;">


#### justify-content

Justify Content works on the **`x-axis`**
Justify content property takes **6** values below:

<img src="./assets/justify-content-flex.png" alt="justify content Flex">

-  `justify-content: flex-start;`
<img src="./assets/justify-content-flex-start.png" alt=" justify-content: flex-start;">

-  `justify-content: center;`
<img src="./assets/justify-content-center.png" alt=" justify-content: center;">

-  `justify-content: flex-end;`
<img src="./assets/justify-content-flex-end.png" alt=" justify-content: flex-end;">

> Justify Content - Space

<img src="./assets/justify-content-space.png" alt="justify content space">

- `justify-content: space-between`
No gap between the flex item and the flex container but space is distributed equally among the items.
<img src="./assets/justify-content-space-between.png" alt="justify-content: space-between">

- `justify-content: space-around`
<img src="./assets/justify-content-space-between.png" alt="justify-content: space-between">

- `justify-content: space-evenly`
<img src="./assets/justify-content-space-evenly.png" alt="justify-content: space-evenly">

<img src="./assets/justify-content-space-evenly-1.png" alt="justify-content: space-evenly">


#### align-content
Align content works on the **y**-axis.

<img src="./assets/align-content.png" alt="align-content">

- Flex wrap
Gives responsiveness.
<img src="./assets/align-content-center.png" alt="align-content-center">

<img src="./assets/align-content-flex-start.png" alt="align-content-flex-start">

<img src="./assets/align-content-flex-end.png" alt="align-content-flex-end">

#### place-content
- Shorthand for `justify-content` and `align-content`
- `place-content`: `align-content` `justify-content`;

```css
place-content: y-axis x-axis;
/* first takes the align-content values then justify-content values respectively */
```

<img src="./assets/place-content.png" alt="place content shorthand for align-content and justify-content respectively">

#### align-items

<img src="./assets/align-items.png" alt="align-items">

- `align-items: flex-end;`
<img src="./assets/align-items-flex-end.png" alt="align-items: flex-end;">


#### align-self
- It's written on the `flex items` and not the flex container.

<img src="./assets/align-self.png" alt="align-self">

- `align-self: flex-end;`
<img src="./assets/align-self-flex-end.png" alt="align-self: flex-end;">


#### Order property
- Order property starts with **0**.

#### Flex grow | Flex shrink | Flex basis
<img src="./assets/flex-grow-flex-shrink.png" alt="flex-grow-flex-shrink">
<img src="./assets/flex-grow-1.png" alt="flex-grow">
<img src="./assets/flex-grow.png" alt="flex-grow">
<img src="./assets/flex-basis.png" alt="flex-basis">


#### Wrap | Flex wrap | nowrap
<img src="./assets/wrap-flex-wrap.png" alt="wrap-flex-wrap">

#### Flex shorthand
<img src="./assets/flex-shorthand.png" alt="flex-shorthand">
<img src="./assets/flex.png" alt="flex-shorthand">

#### Flex flow
<img src="./assets/flex-flow.png" alt="flex-flow">
<img src="./assets/flex-flow-1.png" alt="flex-flow">


### Flexbox levels - How to use Flex box

> How flex box is used in different webpage sizes (Responsive Web Design) on both `Desktop` and `Mobile` displays. 

#### Level 1 - Card layout
<img src="./assets/flexbox-level1.png" alt="Level 1 - Card layout" >

#### Level 2 - Navbar
<img src="./assets/flexbox-level2.png" alt="Level 2 - Navbar" >

#### Level 3 - Side bar 
<img src="./assets/flexbox-level3.png" alt="Level 3 - Side bar" >

#### Level 4 - Card layout 2 
<img src="./assets/flexbox-level4.png" alt="Level 4 - Card layout 2" >

#### Level 5 - Holy Grail 
<img src="./assets/flexbox-level5.png" alt="Level 5 - Holy Grail" >










