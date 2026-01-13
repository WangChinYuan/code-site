---
layout: default
title: 程式碼展示
parent: 教學導引
nav_order: 1
---

# 程式碼展示區
{: .no_toc }

1. TOC
{:toc}

---

## 為什麼要用 Markdown?

你可以在這裡寫下說明，然後下方展示程式碼。

## Dart / Flutter 範例

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

// 這是一個簡單的 Flutter 範例
class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(title: const Text('Hello Jekyll')),
        body: const Center(child: Text('程式碼高亮成功！')),
      ),
    );
  }
}
```

## JavaScript 範例

```js
console.log("這就是你要的效果！");

function demo() {
  return "Jekyll 很簡單";
}
```
