---
layout: post
title:  "Getting Started with Flutter"
date:   2019-07-10 22:06:25 +0530
categories: flutter
---
> This page is under construction. If something seems incomplete, it's because it probably is.

Basic intro about flutter would go here

This is how an simple hello world program would look like

```dart
import 'package:flutter/material.dart'

void main() => runApp(MainApplication());

class MainApplication extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: HomePage(),
    );
  }
}

class HomePage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text('My First Flutter App')),
      body: Center(child: Text('Hello World!'));
    );
  }
}
```