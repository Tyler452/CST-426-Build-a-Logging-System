# CST-426-Build-a-Logging-System
The Approch: 
I extended the provided Dear ImGui starter project with a global logging system (Log.h / Log.cpp).  
Logs to Visual Studio debug console.
Logs to a text file.
Supports the different log levels such as INFO, WARNING, and ERROR.
an change log level at runtime with Log::SetLevel.

The Integration: 
Application.cpp initializes logging in GameStartUp().
Example log calls were added for INFO, WARNING, and ERROR.
A sample ImGui window allows runtime testing of log messages.
