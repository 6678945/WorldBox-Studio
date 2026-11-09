# Third-Party Notices

WorldBox Studio 的原创代码、页面、模板与原创素材采用 MIT License（见 `LICENSE`）。

随应用分发的第三方软件：

| 组件 | 许可证 | 说明 |
| --- | --- | --- |
| Electron | MIT | 桌面外壳 |
| Chromium | BSD 3-Clause 等 | Electron 内嵌浏览器；完整第三方声明见 Electron 发行包内 `LICENSES.chromium.html` |
| Node.js | MIT | Electron 运行时 |
| Python | PSF License | 内置编辑器服务 |
| PyInstaller | GPLv2 + bootloader exception | Python 服务打包 |
| Pillow | HPND | 图像/图标生成工具链（如被打包） |


| sherpa-onnx-node / sherpa-onnx-win-x64 | Apache-2.0 | 本地 ONNX 推理运行库（随编辑器分发，位于 editor/server/vendor/sherpa） |
| SenseVoiceSmall ONNX 模型 | 由 DSH 语音输入缓存提供 | 模型不随编辑器安装包复制；运行时从 %USERPROFILE%\.dsh\speech-to-text\sensevoice\models\sensevoice-onnx\ 读取 |

语音识别完全在本机 CPU 运行，音频不上传到模型服务；模型文件归其原始发布者所有，使用前请遵守其许可证。

随应用分发的原创内容：

- `editor/assets/icons/`：由 `editor/assets/tools/gen_icons.py` 程序化生成的像素图标；
- `editor/assets/effects/`：WorldBox Studio 程序化生成的原创特效模板；
- `editor/presets/`：WorldBox Studio 原创通用配置模板；
- `knowledge/`：原创说明、匿名化抽象经验与公开规则摘要；
- 不包含任何第三方模组代码、图标、音频、帧序列或数据表。

第三方软件的完整许可证文本以各自发行包/仓库为准。发布或再分发时请保留本文件与 `LICENSE`。
