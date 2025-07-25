# 明末：虚渊之羽 Mod —— 强制显示PS5手柄图标

## 前言

专为使用无线连接DualShock手柄的Steam玩家设计

## 安装方式

1. 启用Steam输入  
2. 前置安装 [RE-UE4SS experimental-latest](https://github.com/UE4SS-RE/RE-UE4SS/releases/tag/experimental-latest)  
（解压安装路径为 `Wuchang Fallen Feathers\Project_Plague\Binaries\Win64\`）  
3. 安装 [本mod](https://github.com/DreamNya/Wuchang_ForcePS5Icons/releases/tag/v1.0)  
（解压安装路径为 `Wuchang Fallen Feathers\Project_Plague\Binaries\Win64\ue4ss\Mods\`）  
4. 开始游戏，无论是何手柄都会被识别为DualShock手柄  

## 后记

辣鸡游戏，2025年了还不识别PS5手柄

由于`.uasset`无法增量更新，故本Mod采用`.lua`动态劫持方法，需要前置安装`UE4SS`而无需`SML`  
除非游戏结构大更新，否则安装本Mod后无需更新  
（如果有使用`.pak`可增量劫持函数的方法，希望能不吝赐教）  

----

# Wuchang Fallen Feathers Mod — Force Display PS5 controller Icons

## Introduction

Specifically designed for Steam players using wireless DualShock controller.

## Installation

1.Enable Steam Input  
2.Install the prerequisite [RE-UE4SS experimental-latest](https://github.com/UE4SS-RE/RE-UE4SS/releases/tag/experimental-latest)  
(Extract to: `Wuchang Fallen Feathers\Project_Plague\Binaries\Win64\`)  
3.Install [this mod](https://github.com/DreamNya/Wuchang_ForcePS5Icons/releases/tag/v1.0)  
(Extract to: Wuchang Fallen Feathers\Project_Plague\Binaries\Win64\ue4ss\Mods\)  
4.Start the game — all controllers will now be recognized as DualShock controllers

## Postscript

Since `.uasset` files can't be updated incrementally, this mod uses dynamic `.lua` hijacking and requires `UE4SS` (no need for `SML`).  
Unless the game's structure changes significantly, you won’t need to update this mod once installed.  
(If you know a way to incrementally hijack functions using `.pak`, please share your knowledge!)  
