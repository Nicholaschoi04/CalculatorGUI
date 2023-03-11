# Instructions  

Make a calculator. It should have the following buttons `+`, `-`, `*`, `/`, `^`, `=`, `clear`. The calculator should have one textbox. The calculator can be in two states. In the first state the calculator has not stored any input from the user. In the first state the user may:
1. Enter a number `x` in the textbox and click one of the operations `+`, `-`, `*`, `/`, `^`, causing the calculator to store the number `x` and the operation `op` and enter the second state.
2. Click `clear` and erase all content from the textbox and remain in the first state.

In the second state, the user may:
1. Enter a number `y` in the textbox and click another operation `+`, `-`, `*`, `/`, `^`. In this case the textbox should display the result of `x op y`, store that result as `x`, the new operation as `op` and remain in the second state.
2. Enter a number `y` in the textbox and click `=`. In this case the textbox should display the result of `x op y` and enter the first state.
3. Click `clear` and erase all content from the textbox and all stored variables `x` and `op` and enter the first state.

The calculator should be able to handle all user input in the appropriate way. If something does not make sense it should inform the user.

|KU|A|T|C|
|-|-|-|-|
|<p align=center>/4</p>|<p align=center>/3</p>|<p align=center>/2</p>|<p align=center>/3</p>|