# Package for Ant Icons

An icon is a graphical representation of meaning. Icons can be used to express actions, state, and even to categorize data. [Ant Design's icons](https://ant.design/components/icon/) adhere to the following two principles and are designed for cross-platform consistency:

- Graphics that are clear, intuitive, and simple enjoy a higher degree of recognition and are more easily understood
- All icons in the user interface should be consistent in style (detail design, perspective, stroke weight, etc.)

This is a Flutter package for Ant Icons.

<p align="center">
<img src="https://gw.alipayobjects.com/zos/rmsportal/XzOPonWCsPjvgkrklCzo.png" width="500">
</p>

## Install

Add the following in you `pubspec.yaml` file under `dependencies:`

```yaml
ant_icons: <latest_version>
```

## Usage

```dart
import 'package:ant_icons/ant_icons.dart';

class HomePage extends StatelessWidget {
  Widget build(BuildContext context) {
    return IconButton(
      icon: Icon(AntIcons.ant_cloud),
      onPressed: () { print('Pressed on Ant Cloud icon'); }
     );
  }
}
```

## Getting Started

This project is a starting point for a Dart
[package](https://flutter.dev/developing-packages/),
a library module containing code that can be shared easily across
multiple Flutter or Dart projects.

For help getting started with Flutter, view our 
[online documentation](https://flutter.dev/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
