
Create the layout displayed in sass_exercise_1_layout.jpg using the rules nesting and the Sass Variables.

You should use the following colors:
* red 
* blue
* green

**Suggestion:**

$color-primary: red;
$color-tertiary: green;

.exercise {
border: 1px solid $color-primary;

    .exercise-title {
        color: $color-tertiary;
    }
}
