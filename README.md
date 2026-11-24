管理员权限打开cmd:

```bat
# 单个文件
mklink "%USERPROFILE%\.config\starship.toml" "%USERPROFILE%\dotfiles\starship.toml"
mklink "%USERPROFILE%\.condarc" "%USERPROFILE%\dotfiles\.condarc"
mklink "%USERPROFILE%\.wslconfig" "%USERPROFILE%\dotfiles\.wslconfig"
mklink "%USERPROFILE%\AppData\Roaming\Rime\default.custom.yaml" "%USERPROFILE%\dotfiles\rime_ice\default.custom.yaml"
mklink "%USERPROFILE%\AppData\Roaming\Rime\rime_ice.custom.yaml" "%USERPROFILE%\dotfiles\rime_ice\rime_ice.custom.yaml"
mklink "%USERPROFILE%\AppData\Roaming\Rime\weasel.custom.yaml" "%USERPROFILE%\dotfiles\rime_ice\weasel.custom.yaml"

# 目录
mklink /D "%USERPROFILE%\.glzr\glazewm" "%USERPROFILE%\dotfiles\glazewm"
mklink /D "%USERPROFILE%\.config\yasb" "%USERPROFILE%\dotfiles\yasb"
mklink /D "%USERPROFILE%\.config\fastfetch" "%USERPROFILE%\dotfiles\fastfetch"
mklink /D "%USERPROFILE%\.pi" "%USERPROFILE%\dotfiles\.pi"
mklink /D "%USERPROFILE%\AppData\Local\nvim" "%USERPROFILE%\dotfiles\nvim"
mklink /D "%USERPROFILE%\AppData\Roaming\nushell" "%USERPROFILE%\dotfiles\nushell"
mklink /D "%USERPROFILE%\AppData\Roaming\yazi" "%USERPROFILE%\dotfiles\yazi"
mklink /D "%USERPROFILE%\AppData\Roaming\jj" "%USERPROFILE%\dotfiles\jj"
```
