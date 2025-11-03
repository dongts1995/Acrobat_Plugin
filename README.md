Adobe Acrobat plugin that can interact with Go lang library (staticly linked with C++ code)

The Go library able to make network requests, such as REST and Websocket client connections to server, without blocking Acrobat main thread.

The plugin + go work on both Mac and Windows

Also, Have installer for both Mac and Windows

The plugin also be able to show QR code using Acrobat UI elements, and some other UI interactivity with user.

Deliverables 

• Installers for the plugin for both Windows and Mac, which places the .api file into the right folder for user. 

• C/C++ plugin uses Acrobat SDK, displays UI elements, including QR code 

• C/C++ plugin includes statically linked Go library 

• Go can call functions in C/C++, to trigger some UI interactivity 

• C/C++ can call functions in Go, to trigger network operations and algorithms.
