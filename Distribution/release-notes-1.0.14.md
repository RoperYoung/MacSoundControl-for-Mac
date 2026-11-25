# NeoSoundControl 1.0.14

修复了使用 iShot 等多输出设备时，单个应用在 100% 有声、调低后突然静音的问题。在主窗口或菜单栏选择“分开控制”，从 90% 拖到 89%、88% 时，应用的输出振幅会随每个百分点逐步降低。拉到 0% 可静音，调高即可恢复播放。

## English

Fixed an issue that could silence an app as soon as its volume dropped below 100% on a multi-output device such as iShot. With separate volume control enabled in the main window or menu bar, moving from 90% to 89% to 88% now lowers the output amplitude at each step. Set an app to 0% to mute it and raise the slider to hear it again.
