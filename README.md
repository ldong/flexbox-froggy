# Flexbox Notes
Date: Wed Jun 28 14:53:08 PDT 2017


Web: http://flexboxfroggy.com/

```
flex-direction: row | row-reverse | column | column-reverse
justify-content: flex-start | flex-end | center | space-between | space-around
align-items: flex-start | flex-end | center | baseline | skretch
order: number;
align-self: auto | flex-start | flex-end | center | baseline | stretch
flex-wrap: nowrap | wrap | wrap-reverse
flex-flow: row wrap
align-content: auto | flex-start | flex-end | center | baseline | stretch
```

*align-content*: determines the spacing between lines
*align-items*: determines how the items as a whole are aligned within the container. When there is only one line, align-content has no effect.

![](./align-content.png)

![](./align-items.png)


## Level 24 Answers
```
flex-direction: column-reverse;
flex-wrap: wrap-reverse;
justify-content: center;
align-content: space-between;
```