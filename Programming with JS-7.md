####  Questions

>  What are the three things you need to provide for a loop? I.e., in for(a ; b ; c){}, what are a, b, and c?


A:    
* The ‘for’ keyword.

* The setup ( initialization ; condition ; final-expression ).

* The code block (what to do within the loop).


>  Describe infinite loops and how to avoid them.


A:  An infinite loop occurs when the condition is always true, so the loop never stops.  Infinite loops can freeze or crash your computer.


#### Code Practice

>  Using the shoppingCart variable below, use a for() loop to iterate over the array and console.log() the shopping cart item's name.

####   Code

```JS
var shoppingCart = [
  {
      id: 0,
      name: 'Mens Shirt',
      price: 20,
      size: 'Large'
  },
  {
  id: 1,
  name: 'kids shirt',
  price: 15,
  size: 'small'
}
]

// write code below
for (let i = 0; i < shoppingCart.length; i++) {
  console.log(shoppingCart[i]);
}
```