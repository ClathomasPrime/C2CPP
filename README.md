# C2CPP
A Transcompiler for the Modern World

It has long been said that C is dying. The modern world has simply moved beyond pointers and grown tired of <code>(int*)malloc(x*sizeof(int))</code>. But with so much code written in C, how are we to move on? This project solves a large portion of this problem, automatically translating many valid C programs into a more modern and usable language, C++. We believe this project shows the true power of source-to-source compilation, as it builds on the mission CoffeeScript and other projects to promote both readability and convenience. 

To use this command line tool, simply supply the name of the C file as the first argument, and the name of the C++ file as the second argument. Leave off the extension both times, as the very intelligent system can figure them out for you. And with that simple sequence, you entire file is on its way! No flags to worry about, just simplicity and modernization.
