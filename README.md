# Converter

A fork of [paradiseduo/Converter](https://github.com/paradiseduo/Converter). Removed some unnecessary steps.

[see more](https://blog.i1nfo.com/posts/ios-crack-sideload/)

## Convert IPA to Mac App (M1 SIP enabled)
requirements:
- decrypted app with [appdecrypt](https://github.com/paradiseduo/appdecrypt) or other tools
- ~~An Apple Developer Account with "teamID.com.*" mobileprovision~~  (You also can resigning by a free Apple ID)
- https://github.com/AloneMonkey/MonkeyDev or https://github.com/DanTheMan827/ios-app-signer

## How to use
```bash
> git clone https://github.com/paradiseduo/Converter.git
> chmod +x build-macOS_arm.sh.sh
> ./build-macOS_arm.sh
> ./converter
Version 1.0

converter is a tool to conver iOS application to macOS application and run with M1.

Examples:
    mac:
        converter Test.ipa

USAGE: converter ipa_path

ARGUMENTS:
  <ipa_path>        The ipa file path.

OPTIONS:
  -h, --help              Show help information.
```

### Example
You must use a Decrypted IPA with developer codesign
```bash
> ./converter ~/Desktop/KingsRaid.ipa
Start converter /Users/minim1/Desktop/KingsRaid.ipa
Finish converter, you can found it in current work directory
```

## Thanks

- https://github.com/Mila432/IPA-to-App-M1
- https://github.com/paradiseduo/Converter
