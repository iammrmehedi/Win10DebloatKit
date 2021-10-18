Win 10 Ultimate Debloat Kit

This Debloat Kit is Provided By THEWORLDOFPC

Youtube: <a href="https://www.youtube.com/theworldofpc" target="_blank">THEWORLDOFPC </a>

Website: <a href="https://nexusliteos.blogspot.com/" target="_blank">THEWORLDOFPC </a>

---------Steps----------

Place "install_wim_tweak" to C:\Windows\
and C:\Windows\System32

Use "Ultimate Debloat Kit By WPC.exe" to Debloat Windows 10

Video Tutorial: https://www.youtube.com/watch?v=7m9BuL-wRHQ

FOR LTSC 1809 USERS:

**REMOVE WINDOWS DEFENDER**

set WS=%SystemRoot%\SystemApps\Microsoft.Windows.SecHealthUI_cw5n1h2txyewy

takeown /f %WS% /r /a > nul

icacls %WS% /reset /t > nul

rmdir /s /q %WS%
