# Başlangıç
Konu Başlıkları
1. [Merhaba Dünya](#merhaba-dünya)
2. pubspec.yaml
3. Kurulum
- Ek Modüller
4. Geliştirme'ye Başlangıç

----
# Merhaba Dünya

```dart
void main() {
  print('Hello, World!');
}
```
```sh
dart merhaba_dunya.dart
```
# Online Test Et
<iframe  width="100%" height="350px" src="https://dartpad.dev/embed-inline.html?id=2fadb7133b4c3fb97e827b00741a927a&split=80"></iframe>

----
# pubspec.yaml
> Dart programlama dili bağımlılıklarını belirtmek için pubspec.yaml dosyasını kullanır.
> Uzantısından anlaşılacağı üzere kendisi yaml formatında bir dosyadır.
> Aşağıdaki örnek Flutter için bir yaml dosyasıdır.


```
name: flutterui
description: A new Flutter project.

version: 1.0.0+1

environment:
  sdk: ">=2.7.0 <3.0.0"

dependencies:
  flutter:
    sdk: flutter
  cached_network_image: ^2.0.0
  fluttertoast: ^3.1.3

  cupertino_icons: ^0.1.2

dev_dependencies:
  flutter_test:
    sdk: flutter


# The following section is specific to Flutter.
flutter:

  # The following line ensures that the Material Icons font is
  # included with your application, so that you can use the icons in
  # the material Icons class.
  uses-material-design: true

  assets:
   - images/a_dot_burr.jpeg
   - images/a_dot_ham.jpeg
```
----
# Kurulum

----
# Ek Modüller

----
# Geliştirmeye Başlangıç



