1. What are the main differences between external, internal, and inline CSS?
Answer: Inline CSS allows you to add styles to specific HTML elements. The internal CSS stylesheet allows you to include CSS code in <head> section of a markup document. External stylesheet works by linking a . css file, containing all the CSS rules, to an HTML document.
2. What is the syntax for class and ID selectors?
Answer: a class selector is a name preceded by a full stop (“.”) and an ID selector is a name preceded by a hash character (“#”).
3. How would you apply a single rule to two different selectors?
Answer: To group CSS selectors in a style sheet, use commas to separate multiple grouped selectors in the style. In this example, the style affects the p and div elements. div, p { color: #f00; }
4. Given an element that has an id of title and a class of primary, how would you use both
    attributes for a single rule?
Answer:
5. What does the descendant combinator do?
Answer: ypically represented by a single space (" ") character — combines two selectors such that elements matched by the second selector are selected if they have an ancestor (parent, parent's parent, parent's parent's parent, etc) element matching the first selector.
6. Between a rule that uses one class selector and a rule that uses three type selectors,
which rule has the higher specificity?
Answer: The one that uses three type of selectors.
7. From inside to outside, what is the order of box-model properties?
Answer:
8. What does the box-sizing CSS property do?
Answer: sets how the total width and height of an element is calculated.
9. 
Answer: If you are using the standard box model, the size of the border is added to the width and height of the box. If you are using the alternative box model then the size of the border makes the content box smaller as it takes up some of that available width and height.
10. Would you use margin or padding to create more space between 2 elements?
Answer: You use a margin to ensure that other elements aren't too close to the element
11. Would you use margin or padding to create more space between the contents of an
    element and its border?
Answer: padding property controls the space inside an element.
12. Would you use margin or padding if you wanted two elements to overlap each other?
Answer: You use a margin.
13. What is the difference between a block element and an inline element?
Answer: Block elements cover space from left to right as far as it can go.
14. What is the difference between an inline element and an inline-block element?
Answer: Inline elements only cover the space as bounded by the tags in the HTML element. Block elements have top and bottom margins.
15. Is an h1 block or inline? 
Answer: They are block elements.
16. Is button block or inline?
Answer: They are inline.
17. Is div block or inline?
Answer: Its a block element.
18. Is span block or inline?
Answer: inline.
19. What’s the difference between a flex container and a flex item?
Answer: Flex Container is the parent element while Flex Item represents the children.
20. How do you create a flex item?
Answer:
21. What are the 3 values defined in the shorthand flex property?
Answer: The default values are set to 1 1 0% (which are the shorthand values for flex-grow flex-shrink flex-basis respectively) probably because these are the values that make the most sense for "flex" items.
22. How do you make flex items arrange themselves vertically instead of horizontally?
Answer:
23. What is the difference between justify-content and align-items?
Answer: justify-content — controls alignment of all items on the main axis. align-items — controls alignment of all items on the cross axis.
24. How do you use flexbox to completely center a div inside a flex container?
Answer: By adding the display: flex; property we make the section element a flex container allowing us to adjust the layout of the div which is now a flex item.
25. What’s the difference between justify-content: space-between and justify-content:
space-around?
Answer: space-between : items are evenly distributed in the line; first item is on the start line, last item on the end line. space-around : items are evenly distributed in the line with equal space around them.

