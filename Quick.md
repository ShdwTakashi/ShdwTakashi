Set objShell = WScript.CreateObject("WScript.Shell")

' The "gentle" opening
objShell.Popup "I gently open the door...", 4, " ", 64

' The immediate follow-up after it closes
MsgBox "The door is now closed.", vbExclamation, "Door Log"
