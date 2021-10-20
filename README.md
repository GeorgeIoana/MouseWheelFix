# Mouse wheel events do not work in the Visual Basic 6.0 IDE
You cannot scroll by using the mouse wheel in the Microsoft Visual Basic 6.0 IDE.

## Solution
Download the VB6 Mouse Wheel.exe file that includes the add-in DLL and the code that is used to create the add-in DLL.

1. Download the VB6 Mouse Wheel.exe file.
2. Click Start, click Run, type regsvr32 <path>\VB6IDEMouseWheelAddin.dll, and then click OK.
4. Start Visual Basic 6.0.
5. Click Add-Ins, and then click Add-in Manager.
6. In the Add-in Manager list, click MouseWheel Fix.
7. Click to select the Loaded/Unloaded check box, and then click to select the Load on Startup check box.
8. Click OK.
