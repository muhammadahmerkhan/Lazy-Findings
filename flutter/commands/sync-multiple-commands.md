If you are worry about executing tens of commands once at a time you can opt a new technique to execute all commands synchronously like this :
```dart
flutter clean ; flutter pub get ; flutter --version 
```
With using semicolon we can break the statement commands but it runs synchronously.
You can also go into any directory and run commands peacefully,
```dart
flutter pub get ; cd ios ; pod install --repo-update ; cd ..
```
