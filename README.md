### flutter_discord_logger

This package is a flutter version of `discord-logger-js`. Refer: https://github.com/johnmelodyme/discord-logger-js

|                 | Android | IOS     |
| --------------- | ------- | ------- |
| **Requirement** | min 16  | min 9.0 |


#### Demo:

![demo](
https://github.com/johnmelodyme/flutter_discord_logger/blob/main/demo.gif?raw=true)


### How to use?

1. Installation
   Add `flutter_discord_logger` to `pubspec.yaml`, and hit command `flutter pub get`.
   or
   run `flutter pub add flutter_discord_logger`

   ```yaml
   dependencies:
     flutter_discord_logger: any
   ```

2. Implementation
   Before implementing, make sure you uderstand the `parameters`.

```dart
    import 'package:flutter_discord_logger/flutter_discord_logger.dart';
```

Example of calling the widget:

```dart
   /// Init Discord
    late final Discord discord = Discord(
    /// Name of your webhook
        appName: 'app',

        /// Your Webhook url
        webhookUrl: webhook.text.toString(),
    );

    discord.send(
        /// Your message
        message: message.text.toString(),
        /// delay, default set to 1
        timer: 2, 
    );
```

### Contribution:

I Would ❤️ to see any contributions. If you do liked my work, show some ❤️ by ⭐ repo.

Also you can appreciate me by buy me a coffee:
<br />
<a href="https://www.buymeacoffee.com/johnmelodymel" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
