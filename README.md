# listings
Improvements/Fixes to the latex listings package.

**DISCALIMER!**
I am not a latex expert and hence have not tested the changes properly. I have only my personal use cases to validate the modifications I've made.

Since I can't seem to get in touch with the current mainteiner of the listings package, I decided to share my fixes and improvements for others to use. 

## Improvements:

1. When using multi-columns option, the caption is not placed inside the first column, but as part of the float and hence "covers" all columns (only tested with two columns).
2. when using linerage in \lstinputlisting line numbers can be automatically derived from the original file. Added two addtional arguments to \lstinputlistints: one to enable this behaviur and another to automatically place \dots between ranges (to indicate the jump). This solution is based on the answer by TheConstructor on [LaTeX Stack Exchange Q.110187](http://tex.stackexchange.com/questions/110187/listings-line-numbers-that-match-the-linerange-specification)

