# CST-426-Build-a-Logging-System
Start with a base Dear IMGUI project for Windows. And add a logging system to this code that you will be using throughout the quarter. This logging system will do two things. It will be able to log to the debug console It should also log its output to a file.

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
