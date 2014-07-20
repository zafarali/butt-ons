butt-ons.css
========
Simple Description: Simple CSS3 buttons with chained, order-independant and forgiving syntax.  

[Check out code examples on the website](http://zafarali.github.io/butt-ons)

## The idea
I was annoyed at the complexity of button libraries out there. Why did i have to `.btn` **AND** `.btn-danger` just to get a red button? Or even more `.btn.btn-default`? Shouldn't `.btn===.btn-default`?  

I created butt-ons for this purpose. All we need to do to create a basic button is: `.butt-on`. If we want it red: `.butt-on-red`. What if we want a big red button? `.butt-on-red-high-wide` or `.butt-on-red-wide-high` or `.butt-on-high-red-wide`. All of these give the same result, you don't need to remember the order!  

## The complete list:
- `.butt-on` - the basic button  
- `.-transp`/`.-transpa..` - inverts the button so the background is transparent, when the user hovers over it turns into the color that we defined/is default.  
- `.-wide` and `.-ultrawide` - makes our buttons wider.  
- `.-high` and `.-ultrahigh` - makes our buttons taller.  
- `.-border` - adds a thin black border to the button  
- `.-over` - overrides the color we specify to default, however, hover color is still the color we decide to have. *refer to the website for more examples*  
- `.-round`/`.-rounde...` - makes our buttons have a rounded border.  

## Colors
Currently we support the following colors:  
1. `.-red`  
2. `.-turq`/`.-turqo...`  
3. `.-green`  
4. `.-blue`  
5. `.-purple`  
6. `.-yellow`  
7. `.-purple`  
8. `.-orange`  
9. `.-offwhite`  
10. `.-grey/gray`  

Creating a new color is as easy as defining the following:
```css
.mynewcolor, .mynewcolor:visited { background-color:...; }
.mynewcolor:hover { background-color:...; }
```
and then adding it as a class to our button:
`<a href="#" class="butt-on mynewcolor">new colors</a>`

## Contributing and Use
Feel free to use this wherever you like, however send me a tweet [@zafarali](http://twitter.com/zafarali) if you do decide to use it! I'd like to see what you do with it.  
Contributions are always welcome!

## Aknowledgements
- Colors inspired by [http://designmodo.github.io/Flat-UI/](designmodo Flat-UI)