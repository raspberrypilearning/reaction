## Waiting for a winner

Let's add code to wait until a button is pressed.

+ After displaying an image, you'll need to wait until someone presses their button.

Another way of saying this is that you'll need to wait as long as button A **and** button B have **not** been pressed.

To do this, add a `while` loop from the 'Control' section. The `while` loop should be added in just after the `draw` block.

![ekran görüntüsü](images/reaction-while.png)

+ Drag an `and` block from 'Logic' to your `while` block:

![ekran görüntüsü](images/reaction-and.png)

+ Drag a `not` from 'Logic' into the left hand side of the `and`:

![ekran görüntüsü](images/reaction-not.png)

+ Drag an `button A is pressed` block from 'Input' to after the `not`:

![ekran görüntüsü](images/reaction-button-a.png)

+ Repeat the 2 steps above to add `not button B is pressed` into the `right` side of your while loop.

![ekran görüntüsü](images/reaction-button-b.png)

+ You can then add a very short (20ms) delay, so that your `while` loop waits as long as a button hasn't been pressed.

![ekran görüntüsü](images/reaction-delay.png)

+ Test your project. Your game should now display an image and then wait as long as buttons A **and** B have **not** been pressed.