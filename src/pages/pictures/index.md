# Computing With Pictures

So far we have computed using numbers, strings, and other simple objects. This is not particularly interesting. From here on out we will focus our attention to computing with pictures, and later to animations. Pictures offer us more immediate creative opportunities, and they make our program output tangible in a way that other methods can't deliver. 

We'll use a library called Doodle to help us with creating graphics. In this chapter we will learn the basics of Doodle.

<div class="callout callout-info">
If you run the examples from the SBT console within Doodle they will just work. If not, you will need to start your code with the following imports to make Doodle available.

```tut:silent
import doodle.core._
import doodle.core.Image._
import doodle.syntax._
import doodle.jvm.Java2DCanvas._
import doodle.backend.StandardInterpreter._
```
</div>
