# batterylevel

A flutter project following 'Writing custom platform-specific code'

See https://docs.flutter.dev/development/platform-integration/platform-channels?tab=android-channel-kotlin-tab for online documentation (retrived 2022.11.17 12.56)

Also check the file <span style="color: #B58900">platform-channels.md</span> for an offline copy of the above page

Just as in the documentation this demo obtains the battery level.

The implementation progress is as shown below:


| HOST OS                    | PLATFORM            | STATUS |
| -------------------------- | ------------------- | ------ |
| Android                    | Kotlin              |  ✔️    |
| Android                    | Java                |  -     |
| Windows                    | C++                 |  ✔️    |
| iOS                        | Objective-C         |  -     |
| iOS                        | Swift               |  -     |

> ✔️ >> implemented  
> <span>-</span> >> Not implemented 
>  
> Note: Using 'platform' to refer to the native implementing technology/language

## Implementation Enviroment
```
[√] Flutter (Channel stable, 3.0.2, on Microsoft Windows [Version 10.0.22000.1219], locale en-US)
[√] Visual Studio - develop for Windows (Visual Studio Community 2022 17.2.6)
[√] Android Studio (version 2021.2)
```

## Use Case
Some functionality could be available through API calls on the host plaform but not yet on flutter. Using this method you can consume the API on the host machine and then simply call the implementation from flutter

The documentation outlines the following ways to achieve this
- MethodChannel
- [Pigeon][pigeon]

This demo utilises <span style="color: #B58900">MethodChannel</span>

## Getting Started With Flutter
A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [pigeon]: <https://pub.dev/packages/pigeon>