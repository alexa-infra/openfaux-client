### Build

* solution has been created with Visual Studio 2012 Prof (express edition does not include MFC/ATL)
* tested on Win7 / IE9. Most probably it works on IE6+ (and from WinXP)
* 64-bit only IE is not supported atm
* current build depends on shared ATL libraries, if you want to distribute it right now, then you will need to include atl too

### Installation

* register add-in for 32-bit Windows

    regsvr32 /i /s "full\path\to\OpenFaux.dll"

* register add-in for 64-bit Windows (but 32-bit IE)
    
    regsvr32 /i /s "full\path\to\OpenFaux.dll"
    c:\Windows\SysWOW64\regsvr32 /i /s "full\path\to\OpenFaux.dll"

* unistall - the same but with /u flag

### Useful link for development

* http://msdn.microsoft.com/en-us/library/bb735854(v=vs.85).aspx
* http://msdn.microsoft.com/en-us/library/windows/desktop/cc144099(v=vs.85).aspx
* http://www.codeproject.com/Articles/1330/Toolband-Toolbar-for-IE-sample-using-WTL
* http://www.codeproject.com/Articles/1323/Internet-Explorer-Toolbar-Deskband-Tutorial
* http://www.codeproject.com/Articles/1957/2Find-Toolbar-for-IE-Yet-Another-Sample