# TaGra - タグとフォルダーを併用した次世代のレイヤー管理手法の提案

## 概要

TaGra（Tag + Graphic）は、レイヤーの複雑さを「タグ」で整理することを目指したペイントソフトです。  
JavaScriptで開発を進めており、従来のレイヤー機能を拡張した新しい管理方法を模索しています。

## 背景と目的
レイヤーには功罪の両面があります。実際、「レイヤー」と「Ctrl+z」だけで、デジタルがアナログと異なる点の大半を説明できると言っても過言ではありません。<br>
しかし、一般的なペイントソフトでは、作品制作の過程でレイヤー数が100を超えることも珍しくなく、  
フォルダ構造が深くなることで管理が煩雑になるという課題があります。  
これは商業・趣味に関わらず、デジタルイラストにおける構造的な問題です。

文書管理ソフトなどでは、フォルダとタグを併用した整理手法が広まりつつありますが、  
ペイントソフトのレイヤー管理は1980年代から大きく変わっていません。  
以上のことに問題意識を持ち、自分なりの解決策を実装して使用感を確かめることを目的に、開発を始めました。

## 実装済み機能（2025年5月時点）
- シンプルな描画機能
- レイヤーの追加・並び替え

## 今後の実装予定機能

- 投げなわ塗り機能
- フォルダ機能
- 筆圧検知
- タグ機能
- タグによる自動命名・分類
- タグの階層関係に基づいた自動フォルダ整理機能
- Pythonを用いた機械学習による筆圧キャリブレーション

# TaGra - A Next-Generation Painting Software with Tag-Based Layer Management

## Overview

TaGra (Tag + Graphic) is a painting software project that aims to simplify the complexity of layer management using a tag-based system.  
The software is being developed in JavaScript and explores a new way of managing layers by extending conventional functionality.

## Background and Purpose

Layer-based editing has both strengths and drawbacks.  
In most painting software, it is not uncommon for a project to contain over 100 layers,  
which often results in deeply nested folder structures that become difficult to manage.  
This is a structural issue in digital illustration, affecting both professional and personal workflows.

In contrast, many document management tools are evolving toward hybrid systems that combine folders and tags.  
However, layer management in painting software has not significantly changed since the 1980s.  
Recognizing this as a core problem, I began developing this project to explore and validate an alternative approach through hands-on implementation.

## Features Implemented (as of May 2025)

- Basic drawing tools  
- Layer addition and reordering

## Planned Features

- Lasso fill tool  
- Folder support  
- Pen pressure detection  
- Tag-based layer management  
- Automatic layer naming and classification based on tags  
- Automatic folder organization using a predefined tag hierarchy  
- Pen pressure calibration using machine learning in Python

