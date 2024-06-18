# 适用于Unity的改进型LitJson库

# 基于 `https://github.com/XINCGer/LitJson4Unity` 二次包装

该库主要服务于 `https://github.com/AlianBlank/GameFrameX` 作为子库使用。

# 使用方式(三种方式)

1. 直接在 `manifest.json` 文件中添加以下内容
   ```json
      {"com.gameframex.unity.xincger.litjson": "https://github.com/AlianBlank/com.gameframex.unity.xincger.litjson.git"}
    ```
2. 在Unity 的`Packages Manager` 中使用`Git URL` 的方式添加库,地址为：https://github.com/AlianBlank/com.gameframex.unity.xincger.litjson.git

3. 直接下载仓库放置到Unity 项目的`Packages` 目录下。会自动加载识别

# 改动功能

1. 增加 `link.xml` 的裁剪过滤
2. 增加 `LitJsonCroppingHelper` 防裁剪脚本

---------------------------------------------------------------

### 简介

基于[原生的LitJson库](https://github.com/LitJSON/litjson)改造的适用于Unity的LitJson库。  
**`支持以下原生版本不支持的特性`**：

* 支持float类型(最新原生版本已经支持)
* 支持Unity内建类型(Vector2、Vector3、Rect、AnimationCure、Bounds、Color、Color32、Quaternion、RectOffset等）
* 支持JsonIgnore Attritube，对某些字段跳过序列化
* 支持对输出的Json内容格式化，更规整

### 博客教程

* [【Unity游戏开发】跟着马三一起魔改LitJson](https://www.cnblogs.com/msxh/p/12541159.html)

