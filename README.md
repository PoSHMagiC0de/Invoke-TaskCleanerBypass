# Invoke-TaskCleanerBypass
My take on the Win10 Task Cleaner UAC bypass.

This is in very rough stages and just a PoC.

### Usage

Invoke-TaskCleanerBypass -Method File -Filename .\Documents\myscript.ps1 -hide

Invoke-TaskCleanerBypass -Method Encoded -EncodedCommand "bgBvAHQAZQBwAGEAZAA="


If you use the File Method, you have to use the Filename parameter to put in the file path.

If you use the Encoded method, you have to use the EncodedCommand parameter to enter a unicode base64 encoded command.
