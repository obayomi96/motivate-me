# Motivate-me
- version 1.0.2


### Current Feature
- Generates random motivational quotes.
- Can be used on events or time intervals


### Example usage

```
import motivation from '@obayomi/motivation.me';

const yourFumction = () => {
  const quote = motivation(); //  the 'quote' variable is now a randomly generated quote
  console.log(typeof(quote)) // string
  document.getElementById('quote').innerHTML = quote;
}
  
// Use youFunction as you wish
```


### Author
- Martins Obayomi
