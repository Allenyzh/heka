# --- 外观设置 ---
# 字体设置（建议安装 JetBrainsMono Nerd Font 或 Cascadia Code）
font-family = "JetBrainsMono Nerd Font"
font-size = 14

# 主题（Ghostty 内置了上百种主题，可以用 ghostty +list-themes 查看）
theme = catppuccin-macchiato

# 窗口透明度 (0.0 到 1.0)
window-background-opacity = 0.95
# 窗口毛玻璃效果 (仅限 macOS)
window-background-blur-radius = 20

# 隐藏窗口标题栏（让界面更极简，macOS 推荐）
window-title-font-family = "JetBrainsMono Nerd Font"
macos-titlebar-style = hidden

# --- 功能设置 ---
# 启用字体连字 (-> 变成 箭头)
font-feature = calt
font-feature = liga

# 鼠标自动隐藏
mouse-hide-while-typing = true

# 复制时去除末尾换行符
copy-on-select = true

# --- 快捷键映射 (Keybinds) ---
# 快速分屏 (借鉴了常用逻辑)
keybind = super+d=new_split:right
keybind = super+shift+d=new_split:down

# 在分屏间切换 (Command + 方向键)
keybind = super+left=goto_split:left
keybind = super+right=goto_split:right
keybind = super+up=goto_split:up
keybind = super+down=goto_split:down

# 快速缩放某个分屏 (类似 tmux 的 Zoom)
keybind = super+shift+f=toggle_split_zoom
