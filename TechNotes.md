Tech Notes
===========

Just a compilation of useful notes so I don't run into the same problem twice

- If you have the correct output but the release test is still failing then you are probably either printing to standard error when you should be printing to standard output, or vice versa.
- If you try to output to a file and it goes to the screen you're probably printing to standard error and not standard output