# CSS Layout - The position Property

The position property specifies the type of positioning method used for an element.

There are five different position values:

    static
    relative
    fixed
    absolute
    sticky

Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the position property is set first. They also work differently depending on the position value.

### position: static;

HTML elements are positioned static by default.

Static positioned elements are not affected by the top, bottom, left, and right properties.


### position: relative;

An element with position: relative; is positioned relative to its normal position.


### position: fixed;

An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

A fixed element does not leave a gap in the page where it would normally have been located.


### position: absolute;

An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).


### position: sticky;

An element with position: sticky; is positioned based on the user's scroll position.

---

# Useful Links

[CSS Layout - The position Property - w3schools](https://www.w3schools.com/Css/css_positioning.asp)
