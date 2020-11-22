# Başlangıç
Konu Başlıkları
1. [Merhaba Dünya](#merhaba-dünya)
2. [pubspec.yaml](#pubspecyaml)
3. [Kurulum](#kurulum)
4. [Geliştirme'ye Başlangıç](#geliştirmeye-başlangıç)

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


```yaml
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
> Dart SDK (Software Development Kit) Kurulumunu Gerçekleştirmek için aşağıdaki yönergeleri izleyebilirsiniz.

[Güncel Kurulum Yönergeleri](https://dart.dev/get-dart)

Linux Ubuntu-Debian
```sh
 sudo apt-get update
 sudo apt-get install apt-transport-https
 sudo sh -c 'wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -'
 sudo sh -c 'wget -qO- https://storage.googleapis.com/download.dartlang.org/linux/debian/dart_stable.list > /etc/apt/sources.list.d/dart_stable.list'

```
Ardından Dart SDK Kurulumu Yapılır.
```sh
 sudo apt-get update
 sudo apt-get install dart
 # Son olarak path değişkeninize flutter yolunu ekleyin
 echo 'export PATH="$PATH:/usr/lib/dart/bin"' >> ~/.profile
```


----
# Geliştirmeye Başlangıç
Yukarıdaki kurulum aşamalarını yaptıktan sonra, Geliştirmey başlayabilmek için ihtiyacınız olan araç bir metin editorü.

[Visual Studio Code](https://code.visualstudio.com/)

[Eclipse](https://github.com/eclipse/dartboard)

[Atom](https://atom.io/)