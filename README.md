# best_flutter_ui_templates

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# [universal_io](https://pub.dev/packages/universal_io)
解決Chrome預覽時不支援問題
## pubspec.yaml
於pubspec.yaml的dependencies下加入universal_io: ^1.0.1
(請注意縮排，多一個少一個都不行)
<br/>
```yaml
dependencies:
  universal_io: ^1.0.1
```
終端機執行：
```
$ flutter pub get
```
於main.dart引用：
```dart
import 'package:universal_io/driver.dart';
import 'package:universal_io/driver_base.dart';
import 'package:universal_io/io.dart';
import 'package:universal_io/prefer_sdk/io.dart';
import 'package:universal_io/prefer_universal/io.dart';
```