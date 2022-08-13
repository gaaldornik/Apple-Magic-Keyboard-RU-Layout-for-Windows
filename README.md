# Apple-Magic-Keyboard-RU-Layout-for-Windows

Description
-
	Entire EN layout is available inside this layout for convenience via Ctrl+Alt, Ctrl+Alt+Shift,
	 e.g. Ctrl+Alt+1 gives you '1', Ctrl+Alt+Shift+1 - '!'... etc

	Volume keys can be mapped using PowerToys official Microsoft app.


Installation
-
	Compatibility
	-
		✓ Windows 11

	• Run Setup.exe
	• Reboot
	• Settings > Time & language > Type & region > Language > Russian > ••• > Language options > Keyboards
		- You should see "Russian (Apple)" in the list, if it's not just add it by clicking "Add a keyboard"
		- Remove unnecessary layouts


Uninstallation
-
	• Delete KBDAMKRU.DLL in C:\Windows\SysWOW64, C:\Windows\System32

	• HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Keyboard Layouts\
		Remove a0000419 necessary folders in the end

	• HKEY_USERS\...\Software\Microsoft\Installer\Products
		Use search string 'Russian (Apple Magic Keyboard)' to find exact location
