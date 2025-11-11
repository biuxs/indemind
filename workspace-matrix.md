在安装 workspace matrix 前要保证安装 Gnome shell 兼容的版本，查看 Gnome shell 的版本指令 gnome-shell --version
从gnome shell拓展网站安装
https://extensions.gnome.org/#sort=relevance



To install Workspace Matrix, click to toggle the "Off" icon on the extension page. A red "ERROR" icon can safely be ignored. This issue is resolved after a restart of GNOME Shell.
Restart GNOME Shell.
To configure the extension, return to the extension page page and click the blue "tool" icon.


重启 GNOME Shell 的方法（🧭 一、判断当前 Ubuntu 是否在用 Wayland 还是 X11
✅ 方法 1：命令行判断

打开终端，输入：

echo $XDG_SESSION_TYPE


输出结果是：

wayland → 你在用 Wayland

x11 → 你在用 X.org）
If you are running the newer Wayland system, log out and log back in.
If you are running the X.org/X window system, press Alt+F2, type r in the "Run a command" prompt and press Enter.
