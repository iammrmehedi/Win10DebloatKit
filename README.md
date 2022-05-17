<p align="center">
  <img src="https://user-images.githubusercontent.com/89072438/168904994-7103c4f4-1925-4d92-9418-4b83670b64c0.png" alt="Screenshot">
  </p>
  
<h1 align="center"> Win 10 Ultimate Debloat Kit. </h1>

<h4 align="center">This Debloat Kit is Provided By THEWORLDOFPC. </h4>

# Download:
<a href="https://www.mediafire.com/file/scg32zd31y5ewod/Windows_10_Ultimate_Debloater_By_WPC.zip/file" >Mediafire</a>
# Social:
- Youtube: <a href="https://www.youtube.com/theworldofpc" target="_blank">THEWORLDOFPC </a>
- Website: <a href="https://nexusliteos.blogspot.com/" target="_blank">THEWORLDOFPC </a>

# Steps to Use this Tool:

- Copy "install_wim_tweak.exe" to C:\Windows\ and C:\Windows\System32
- Then run "Ultimate Debloat Kit By WPC.exe" as administrator to Debloat Windows 10

# Video Tutorial: 
<a href="http://www.youtube.com/watch?feature=player_embedded&v=7m9BuL-wRHQ
" target="_blank"><img src="http://img.youtube.com/vi/7m9BuL-wRHQ/0.jpg" 
alt="Tutorial"  /></a>


# FOR LTSC 1809 USERS:

REMOVE WINDOWS DEFENDER
- set WS=%SystemRoot%\SystemApps\Microsoft.Windows.SecHealthUI_cw5n1h2txyewy
- takeown /f %WS% /r /a > nul
- icacls %WS% /reset /t > nul
- rmdir /s /q %WS%
