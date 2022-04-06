# Installing Powerline fonts on Windows 10

## Steps

1. Download and extract zip from https://github.com/powerline/fonts
2. Press `Windows + x`
3. Press `a` (Selects PowerShell (Admin)
4. Navigate to directory where fonts were extracted to (`cd ${HOME}\Downloads\fonts-master\fonts-master`)
5. Set Execution policy `Set-ExecutionPolicy Bypass`
6. Press `y` then `Enter` to accept
7. Run the install file `.\install.ps1`
8. Reset Execution policy `Set-ExecutionPolicy Default`
9. Press `y` then `Enter` to accept
10. Remove the fonts folder (`cd ../.. && Remove-Item -Recurse -Force fonts-master`)

### Resources
- https://medium.com/@slmeng/how-to-install-powerline-fonts-in-windows-b2eedecace58
- https://github.com/powerline/fonts
