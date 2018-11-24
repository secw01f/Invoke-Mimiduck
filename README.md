# Invoke-Mimiduck
USB Rubber Ducky scripts using a manipulated version of Invoke-Mimikatz to extract passwords and write them to a file. The Invoke-Mimiduck.txt duckyscript uses the PowerShell script directly on the Twin Duck and the Invoke-Mimiduck-Remote.txt duckyscript calls the PowerShell file in this repository remotely.

***
The babayega.ps1 file is a modified version of Invoke-Mimikatz.ps1 but may need further obfuscation to bypass AV if being used for real world testing.

# Install

1. Flash the Rubber Ducky to create a Twin Duck. (for instructions visit https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Flashing-ducky )
2. Use duckencoder.jar, or https://ducktoolkit.com to encode the selected duckyscript to create your inject.bin file.
3. If using Invoke-Miniduck.txt file you will need to put the PowerShell file on the Rubber Ducky.
4. HAVE FUN!
