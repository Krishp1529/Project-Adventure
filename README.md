Krish Patel kpatel31@stevens.edu

The URL of your public GitHub repo:
https://github.com/Krishp1529/Project-Adventure.git

An estimate of how many hours you spent on the project
4-5 hours

A description of how you tested your code
The code was tested for map given in the description manually by using the implemented commands in different combination pattern to check for any error.

Any bugs or issues you could not resolve
During development, I encounter bugs or issues related to parsing player input, handling edge cases, or managing game state updates.

An example of a difficult issue or bug and how you resolved
One difficult issue could be handling complex commands with multiple parameters. To resolve this, you can implement a flexible command parsing system that can recognize different patterns of input and extract relevant information.

A list of the three extensions you’ve chosen to implement, with appropriate detail on them for the CAs to evaluate them (i.e., what are the new verbs/features, how do you exercise them, where are they in the map) :
help: prints the player all the valid commands/verbs onto screen
drop: If the object is in the inventory, it will get added to the Items list of the current room and If it's not in the inventory then you a message will get printed "No such item in the inventory".
direction abbreviation: Instead of using complete go command (go + direction) user can type shortcuts such as n, s, e, w etc. to move the character