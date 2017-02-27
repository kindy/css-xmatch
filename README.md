# css-xmatch


## scroll-match

[Prototype Demo](https://codepen.io/kindy/pen/vxEoQN?editors=0100) at codepen.

```less
[x-scroll-match="y=0"] {
  // when scroll is at top
}

// or: body[x-scroll-match="y<=50vh"] .go-top {
body:not([x-scroll-match="y>50vh"]) .go-top {
  display: none;
}

```
