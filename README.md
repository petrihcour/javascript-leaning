# JavaScript Learning - My Notes

## When should I use const, let, and var?

const: Const should be what is primarily used. Const variables cannot be reassigned. This can help keep your code cleaner. A note, however, is you can change the values inside of an object or array created with const.  
        Example: `const cart = { item: "kombucha", price: 5.99, flavor: "raspberry" };
                 cart.price = 6.49;
                 cart.flavor = "lemongrass";`
let: Let should be used when you know you will have to reassign a value. You'll typically see these being reassigned in "for loops" and "if statements".
var: Var should only be used when you're working with older code that is already using it. Beyond that, it should be avoided as it was primarily used in the past before `let` was introduced. 
