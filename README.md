# cpplint
Google CppLint (modified for use with https://github.com/nicmcd/make-c-cpp)

Modifications:
- Doesn't print "Done processing <file>".
- Only prints number of errors when greater than 0.
- Requires the --root flag and uses it exclusively.
- Fixed bug where include header is at the top of the root directory 