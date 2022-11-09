
Modify the exercise 2 code about mixin by creating a module for all declared variables.
Then, create a module with a function. This function should accept a number as parameter and return the value converted into rem. 1rem is equal to 16px
This function should be applied in the main stylesheet, so that the only sizing unit is rem.

**Suggestion:**

@function rem(...
@return calc(...
}

@use "functions" as f;
...
