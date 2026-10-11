# unity

空的 Unity 3D 项目，使用官方 **3D** 模板（`com.unity.template.3d`，内置渲染管线，不是 2D，也不是 URP）。

## 编辑器版本

- 系列：Unity 6.3 LTS
- 版本：`6000.3.26f1`
- Changeset：`de8167e7440c`

请用这一版编辑器打开。同一条 6000.3 LTS 上的其他补丁一般也能打开，Hub 可能会提示升级项目版本。

## 打开方式

1. 用 [Unity Hub](https://unity.com/download) 安装编辑器 **6000.3.26f1**。
2. 在 Hub 里选择 **Open**，选中本仓库根目录（里面有 `Assets`、`Packages`、`ProjectSettings`）。
3. 首次打开需要联网。Package Manager 会按 `Packages/manifest.json` 安装官方 3D 模板的同一组依赖（uGUI、Input System、Timeline、Visual Scripting、Version Control，以及 Development 功能集），版本选用支持 Unity 6 的发行版，并生成 `Packages/packages-lock.json`。编辑器也可能顺手刷新部分 `ProjectSettings`。
4. 打开场景 `Assets/Scenes/SampleScene.unity`。场景里只有 Main Camera 和 Directional Light，没有玩法脚本。

`Library/`、`Temp/`、`Obj/`、`Logs/`、`UserSettings/` 和构建产物已写入 `.gitignore`，不要提交。
