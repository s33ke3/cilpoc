   _______ __               __
  / ____(_) /   ____  _____/ /_______
 / /   / / /   / __ \/ ___/ //_/ ___/
/ /___/ / /___/ /_/ / /__/ ,< (__  )
\____/_/_____/\____/\___/_/|_/____/

PoC of Huawei Smartphone PIN Bruteforce - Bypass 4 Digits PIN using a wordlist

--> Original Tool by LoliC0d3 - Tegal1337 <--
--> Mod by Vincenzo Digilio <--

* Modified Option number 4 --> PoC
* Added sleep Time (10 sec) for avoid incremental time for wrong PIN
* When the correct PIN was found the phone will be automatically unlock
* Added: adb shell input keyevent 82 for KEYCODE_MENU and jump to LockScreen
