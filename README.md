# FnDepot 第三方应用源

飞牛NAS第三方应用仓库，符合 FnDepot 外部源规范。

## 应用列表

| 应用 | 说明 | 平台 |
|------|------|------|
| R1 Toolbox | 海康R1/R1X刷飞牛后的硬件修复与功能增强 | x86 |
| PipeBridge | 基于 PipeWire/BlueZ 的多媒体硬件管理中间层 | x86 |

## 使用方式

在飞牛NAS的 FnDepot 中添加外部源，填入本仓库地址：

```
https://github.com/ZhangZsky/FnDepot
```

## 目录结构

```
FnDepot/
├── fnpack.json          # 应用源索引
├── r1toolbox/           # R1 Toolbox 应用
│   ├── ICON.PNG
│   ├── README.md
│   ├── Preview/
│   │   ├── 1.png
│   │   ├── 2.png
│   │   ├── 3.png
│   │   └── 4.png
│   └── r1.toolbox_x86.fpk
├── PipeBridge/          # PipeBridge 应用
│   ├── ICON.PNG
│   ├── README.md
│   ├── Preview/
│   │   ├── 1.png
│   │   ├── 2.png
│   │   ├── 3.png
│   │   └── 4.png
│   └── PipeBridge_x86.fpk
└── README.md
```