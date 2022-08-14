# hook mods

-key auth hooks application in order to display error messages

-meaning that when ie: key auth implemented in dll for shitty p2c and u unhook it doesnt unhook key auth pattern

- game = crashed





- to do (ideas) (may be shit)

1. implement ability to unhook pattern thats callable from within user app?

2. change log location so instead of annoying asf error popup box it can be put to function that allows printing to console already implemented within your application

3.re-implement task kill shit and make it "better"?

4. not do shit like this at 4 am



temp changes for testing 15/8/22-

-removed hook

-removed anti debug taskkill shit (like that stops anyone half decent )




# keyauth-cpp-library
KeyAuth C++ Library

This is the source code of the library_x64.lib file from https://github.com/KeyAuth/KeyAuth-CPP-Example

**This is NOT open-source, in respect to copyright usage. Commercial use is prohibited, read below for further clarification**

Mutli Support : x86/x64

## License

Use of this source-code is strictly exclusive to API requests being sent to the https://keyauth.win API, or the API of your self-hosted version of KeyAuth **(wherein you're the ONLY application owner)**

Examples of prohibited use cases include using to send requests to an authentication system you sell to other people (a competitor to KeyAuth) and/or to circumvent the client-side security of KeyAuth. An immedate DMCA takedown will be issued should you be found doing this.
## Different Architectures
x86 :

1- Compile libcurl can be downloaded from curl.se and compiled by x86 Native Tools (Visual Studio Tools)

2- Lib Configuration -> General -> C++ Language Standard ->  ISO C++17 Standard (/std:c++17)

3- Lib Configuration -> Advanced -> Character Set ->  Multi-Byte Character Set

4- Lib Configuration -> Preprocessor definiton for CURL -> CURL_STATICLIB
