---
layout: page
title: OutEdge 边界之外
---

# 欢迎来到OutEdge官方网站

## 简介
OutEdge是一个基于Unity3d开发的沙盒类型游戏，运用MarchingCubes算法，构建了一个平滑的世界供玩家探索，玩家还可以自主制造自定义工具、载具，在游戏中存活下去。

包含流体模拟、空气动力、热力、化、电学系统，增加游戏可玩性

独特的工具制造系统，给工具的每一个赋予物理特性。所以在制造工具的同时需要考虑可行性，否则造出来的工具无法使用或容易损坏。

## 背景故事

## 游戏玩法

## 网页试玩

<head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | OutEdge</title>
    <script src="game/TemplateData/UnityProgress.js"></script>
    <script src="game/Build/UnityLoader.js"></script>
    <script>
      var unityInstance = UnityLoader.instantiate("unityContainer", "game/Build/outedge.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
    <div class="webgl-content">
      <div id="unityContainer" style="width: 960px; height: 600px"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="unityInstance.SetFullscreen(1)"></div>
      </div>
    </div>
  </body>