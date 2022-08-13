# Apple-Magic-Keyboard-RU-Layout-for-Windows

Description
-
	Entire EN layout is still available via Ctrl+Alt, Ctrl+Alt+Shift,
	 e.g. Ctrl+Alt+1 gives you '1', Ctrl+Alt+Shift+1 - '!'.

	Volume keys can be mapped using PowerToys official Microsoft app.


Installation
-
	Compatibility
	-
		✓ Windows 11

	• Run Setup.exe
	• Reboot
	• Settings > Time & language > Type & region > Language > Russian > ••• > Language options > Keyboards
		- You should see "Russian (Apple)" in the list, 
		  if it's not just add it by clicking "Add a keyboard"
		- Remove unnecessary ones


Uninstallation
-
	• Delete custom .dll with the name of layout, e.g. Layout03.dll in
		C:\Windows\SysWOW64
		C:\Windows\System32

	• HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Keyboard Layouts\
		Remove a0000419 necessary folders in the end

	• HKEY_USERS\...\Software\Microsoft\Installer\Products
		Use search to find that
