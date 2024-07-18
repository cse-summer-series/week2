# Introduction to UTF-8

The starter code is a cleaned up version from the videos:

- [Inspecting Character Data](https://youtu.be/e8jaxN9EBZQ)
- [Working with UTF-8](https://youtu.be/M604Z8OaSgo)

The documentation links from the videos are here:

- https://en.wikipedia.org/wiki/UTF-8
- https://www.compart.com/en/unicode/U+00E9
- https://www.compart.com/en/unicode/U+674E

The task for this week is to fill in the function `bytes_for(char* unicode, unsigned int n)`.

That function should take a UTF-8 string and a character count, and return the number of *bytes* in that UTF-8 string taken up by the first `n` characters.

Examples:

```
bytes_for("José", 3) -> 3
bytes_for("Ülo", 3) -> 4
bytes_for("José", 4) -> 5
bytes_for("成龙", 1) -> 3
bytes_for("成龙", 2) -> 6
bytes_for("成龙", 3) -> -1
```

Feel free to share questions and comments about this on the Discord!

Avoid posting full solutions just to make sure folks can figure it out on their own if they want. Do feel free to show posts with incomplete code or code with errors/surprising behavior, though!
