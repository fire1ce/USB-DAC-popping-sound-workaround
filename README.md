# macOS Click Fixus

Solving macOS (10.12+) issue of clicking impulse sound before and after playing any sound.

Download application: https://github.com/fire1ce/macClick/raw/main/macOSClickFixusApp.zip 

Unzip.
Copy to Application folder.
* Drag-n-Drop to [System Configuration] -> [Users And Groups] -> [Login Items] to run it on each login.


## Windows

Enable the hidden control panel settings by editing C:\Program Files\FiiO\FiiO_Driver\W10_x64\FiiOCplApp.xml (disable read-only and open your text editor as administrator) and change PageOptions's <Visibility> setting from "Hidden" to "Visible". (Or replace the file with the attachment in the post above.)

Restart the control panel, and then in Options->Streaming, change "On when Needed" to "Always On"
