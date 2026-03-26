# restart_ibus
解决ubuntu系统键盘卡死问题

Bash：

echo "[Desktop Entry]
Name=重启键盘
Name[zh_CN]=重启键盘
Exec=/home/ubt2204/restart_ibus.sh
Path=/home/ubt2204/
Terminal=false
Type=Application
Icon=input-keyboard" > ~/Desktop/ibus.desktop

chmod +x ~/桌面/ibus.desktop
