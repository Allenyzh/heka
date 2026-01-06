# --- 🎨 外观颜值 (Aesthetics) ---

# 字体：推荐 JetBrainsMono NF，如果没有安装，Ghostty 会回退到默认字体
# 开启连字特性 (Ligatures)，让代码符号更漂亮
font-family = "JetBrainsMono Nerd Font"
font-size = 14
font-feature = "calt"
font-feature = "liga"
font-thicken = true  # 让字体稍微加粗一点点，在高分屏上看着更实

# 主题：Tokyo Night (深色背景，色彩丰富但不刺眼)
theme = tokyo-night

# 窗口背景：恰到好处的透明 + 毛玻璃模糊
window-background-opacity = 0.92
window-background-blur-radius = 20

# 布局：给文字四周留出呼吸空间，不再紧贴窗口边缘
window-padding-x = 12
window-padding-y = 12

# 标题栏：使用“透明”风格，让背景色延伸到标题栏，看起来更现代
# (Linux 下如果不支持会忽略此项)
macos-titlebar-style = transparent
macos-option-as-alt = true

# --- 🖱️ 光标与交互 (Cursor & Mouse) ---

# 光标风格：方块且闪烁，经典复古感
cursor-style = block
cursor-style-blink = true

# 鼠标：打字时自动隐藏鼠标，防止遮挡视线
mouse-hide-while-typing = true
# 滚动：稍微调快一点滚动速度
mouse-scroll-multiplier = 2

# --- ⚡️ 高效快捷键 (Workflow) ---
# 使用 Super 键 (Mac上是Command, Linux上是Win键)

# 1. 像管理浏览器一样管理标签页
keybind = super+t=new_tab
keybind = super+w=close_surface
keybind = super+1=goto_tab:1
keybind = super+2=goto_tab:2
keybind = super+3=goto_tab:3

# 2. 分屏神器 (不用记复杂的 Tmux 快捷键)
# Super + D : 向右分屏
keybind = super+d=new_split:right
# Super + Shift + D : 向下分屏
keybind = super+shift+d=new_split:down

# 3. 在分屏之间“瞬移” (使用 Alt/Option + 方向键)
keybind = alt+left=goto_split:left
keybind = alt+right=goto_split:right
keybind = alt+up=goto_split:up
keybind = alt+down=goto_split:down

# 4. 专注模式：按 Super + Z 最大化当前分屏 (再按一次还原)
keybind = super+z=toggle_split_zoom

# 5. 快速重载配置 (改完配置按下这个立即生效)
keybind = super+shift+r=reload_config
