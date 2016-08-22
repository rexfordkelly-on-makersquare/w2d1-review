# Warmup

## Instructions

1. In your starter project, open the files in the `w2d2` directory. 
2. Find a partner (preferably one that you have not yet worked with), and work
   through the following exercises as a pair.

## Exercises

1. Discuss the differences between repetition with a `while` loop and the other
   form(s) of repetition that we have encountered with your partner until you
   are confident that you could describe these differences to the class.

2. The following function is *supposed* to compute the sum of the numbers from 0
   to `n`, but is currently broken (in multiple ways) -- fix it so that it works
   correctly.

   ```js
   function sum(n) {
     var result;
     while (n > 0) {
       result = n + n;
       n = n + 1;
     }
   }
   ```

3. The `power_iter` function from the lecture looks like this:

   ```js
   function power_iter(base, exponent) {
     var result = 1;
     while (exponent > 0) {
       result = result * base;
       exponent = exponent - 1;
     }
     return result;
   }
   ```

   The `power_iter` function counts **down** from `exponent`, iterating as long
   as `exponent` is greater than `0`. Change the implementation so that
   `power_iter` counts **up** from `0` to `exponent`.
