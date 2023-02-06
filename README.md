# test_package_info_plus

Project to validate behaviour of package_info_plus

## Testing

Please open the project and run it on desired platform.

Change the `version` parameter on `pubspec.yaml` to see the results of the
different tests.

You should see results in two places.

### 1. Logs

Example from `macOS` platform
```
flutter: appName: test_package_info_plus
flutter: packageName: com.example.testPackageInfoPlus
flutter: version: 1.2.3
flutter: buildNumber: 4
```

### 2. UI

It should display the values as logs.


# Results

## Test 1

Test using version `1.2.3+4` on `pubspec.yaml`

### macOS

```
flutter: appName: test_package_info_plus
flutter: packageName: com.example.testPackageInfoPlus
flutter: version: 1.2.3
flutter: buildNumber: 4
```


### Chrome (web)

```
appName: test_package_info_plus
packageName: test_package_info_plus
version: 1.2.3
buildNumber: 4
```

### iOS

```
flutter: appName: Test Package Info Plus
flutter: packageName: com.example.testPackageInfoPlus
flutter: version: 1.2.3
flutter: buildNumber: 4
```

### Android

```
I/flutter (13256): appName: test_package_info_plus
I/flutter (13256): packageName: com.example.test_package_info_plus
I/flutter (13256): version: 1.2.3
I/flutter (13256): buildNumber: 4
```

### Linux


### Windows

```
Launching lib\main.dart on Windows in debug mode...
lib\main.dart:1
Connecting to VM Service at ws://127.0.0.1:33238/Gh9UXXAGuYM=/ws
flutter: appName: test_package_info_plus
flutter: packageName: test_package_info_plus
flutter: version: 1.2.3
flutter: buildNumber: 4
```

### Edge

```
Flutter Web Bootstrap: Programmatic
appName: test_package_info_plus
packageName: test_package_info_plus
version: 1.2.3
buildNumber: 4
```



## Test 2

Test using version `1.2.3-beta` on `pubspec.yaml`

### macOS

```
flutter: appName: test_package_info_plus
flutter: packageName: com.example.testPackageInfoPlus
flutter: version: 1.2.3
flutter: buildNumber: 1.2.3
```


### Chrome (web)

```
appName: test_package_info_plus
packageName: test_package_info_plus
version: 1.2.3-beta
buildNumber: ''
```

### iOS

```
flutter: appName: Test Package Info Plus
flutter: packageName: com.example.testPackageInfoPlus
flutter: version: 1.2.3
flutter: buildNumber: 1.2.3
```

### Android

```
I/flutter ( 5659): appName: test_package_info_plus
I/flutter ( 5659): packageName: com.example.test_package_info_plus
I/flutter ( 5659): version: 1.2.3-beta
I/flutter ( 5659): buildNumber: 1
```

### Linux

### Windows

### Edge
