
---

**Problem: BxlendExchange Sequence**

Write a JavaScript function that generates a sequence of numbers from a given starting number to an ending number. However, there are a few additional rules for generating the sequence:

- For numbers divisible by 3, instead of the number, print "Bxlend".
- For numbers divisible by 5, instead of the number, print "Exchange".
- For numbers divisible by both 3 and 5, print "BxlendExchange".
- For all other numbers, simply print the number itself.

Your task is to complete the function `bxlendExchangeSequence` that takes in two parameters: `start` and `end`. The function should return an array containing the sequence of numbers generated according to the rules mentioned above.

**Example:**

```javascript
const start = 1;
const end = 20;
const sequence = bxlendExchangeSequence(start, end);
console.log(sequence);
```

**Expected Output:**

```
[1, 2, "Bxlend", 4, "Exchange", "Bxlend", 7, 8, "Bxlend", "Exchange", 11, "Bxlend", 13, 14, "BxlendExchange", 16, 17, "Bxlend", 19, "Exchange"]
```

---
