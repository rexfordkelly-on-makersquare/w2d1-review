# Self Challenge

## Instructions

1. In your starter project, open the files in the `challenge1` directory.
2. Complete this exercise **individually, not in pairs**.
3. **If you need help understanding the instructions, please ask for help! Your instructor is happy to help clarify the instructions.**
4. **Attempt to complete each exercise -- if you are working on an exercise for longer than ten minutes, move on to the next one.**
5. Afterwards, please **submit your answers** via Slack (we'll cover how to do this after the time is up)!

## Exercises

1. Write a function called `billTotal` that can be used to calculate the total
   to be paid at a restaurant -- including *tip* and *tax* -- given the
   *subtotal* (*i.e.* cost of food and drinks). We can assume that the tip will
   be 15% and tax will be 9.5%. Make sure that the tip does not include the tax!

2. Implement the function called `animalNoise` that accepts two parameters: a
   type of animal and an *emotion* that indicates that animal's current
   emotional state. Based on the combination of `animal` and `emotion`,
   `animalNoise` should return an appropriate noise (represented as a string).
   The function should work with at least two different animals and emotions.

   ```js


   function animalNoise(animal, emotion) {
   // TODO: your code here
   }


   ```

   Some ideas include:

   + **Animals:** cat, dog, horse, duck, chicken, cow, human
   + **Emotions:** angry, happy, sad, surprised

   If you're feeling uninspired, feel free to use "smileys" to convey emotion.

3. The *digital sum* of a number is the sum of all its digits, *e.g.*
   `digitalSum(1337)` should output `14`: `1 + 3 + 3 + 7`. Use **any** of the
   methods of reptition that we have covered so far to implement this function.

   ```js
   function digitalSum(n) {
     // TODO: your code here
   }
   ```

   **HINTS:** Try the following at a console:

   ```js
   1337 % 10;
   133 % 10;
   13 % 10;
   1337 / 10;
   Math.floor(1337 / 10);
   Math.floor(133 / 10);
   ```

   What should `digitalSum` of a single-digit number return, *e.g.* `digitalSum(8)`?
