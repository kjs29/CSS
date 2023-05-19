# This repository contains my notes on HTML/CSS

`CSS questions`

## What keyword controls when the child content is too large for the parent container?

<details>

  <summary>answer</summary
  
  overflow
</details>
    
## What is the name of the space that is in between the content and the border?

<details>

  <summary>answer</summary
  
  padding
</details>
    
## Explain what the following CSS does.

```css
div.headline {
  width: 300px;
  margin: 0 auto;
}
```
    
<details>

  <summary>answer</summary
  
  `div.headlin` has the width of 300px, and 0 margin vertically, and it is centered horizontally.
</details>
    
## In the sample code below, the element with ID “one” is directly above the element with ID “two” in the HTML document. How much space is between the border of element #one and the border of element #two?

    
```cs
#one {
  margin: 20px;
}
 
#two {
  margin: 30px;
}
```

<details>

  <summary>answer</summary
  
  30px
    
  vertical margins don't add together, but it collapses the larger value of the two.
</details>

    
