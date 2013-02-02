### Mods:

*   adjusted syntax, default min-width


Selector queries and responsive containers
==========================================

This script allows you to apply different class values to an HTML element based on its width. Use it as follows:

    <div data-squery="wide=400px small=max-width:10em">
        <p>Content here</p>
    </div>
    
This will apply a class of `wide` when the element is wider than 400 pixels and a class of `small` when it is narrower than 10 ems. It works in all modern browsers back to and including IE6.

That's all.