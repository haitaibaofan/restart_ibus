# restart_ibus
解决ubuntu系统键盘卡死问题

Bash：

echo "[Desktop Entry]
Name=重启键盘
Name[zh_CN]=重启键盘
Exec=gnome-terminal -- bash -c '/home/ubt2204/restart_ibus.sh; exec bash'
Path=/home/ubt2204/
Terminal=true
Type=Application" > ~/桌面/ibus.desktop

chmod +x ~/桌面/ibus.desktop
