使用方法1:

在Flash Builder 4/4.5中切换到设计模式, 右侧Appearance面板栏找到Project theme, 点击Current theme, 弹出主题选择窗口. 点击Import Theme...找到KingnareBlackTheme.swc, 选择并保存.

使用方法2:

将KingnareBlackTheme.swc文件加入项目libs文件夹中.进入Flex Compiler面板, 
在compiler arguments加入:

	-theme ../libs/KingnareBlackTheme.swc

这种方式在设计模式下不能预览新主题.