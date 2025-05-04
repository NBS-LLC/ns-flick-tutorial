# NativeScript Flick Tutorial

https://docs.nativescript.org/tutorials/build-a-master-detail-app-with-plain-typescript

## Prerequisites

-   [Android Studio](https://developer.android.com/studio)
-   [ASDF](https://asdf-vm.com/)
-   [NativeScript CLI](https://docs.nativescript.org/setup/macos#installing-the-nativescript-cli)
-   [Xcode](https://developer.apple.com/xcode/)

See the following for more detailed instructions: https://docs.nativescript.org/setup/macos

## Tips

-   When using `asdf` create a `~/.tool-versions` to pin your system tools to their original versions.

## Troubleshooting

-   Make sure to have asdf plugins for each of the tools listed in `.tool-versions`.
-   Make sure to `asdf reshim` after installing the NativeScript CLI.
-   If Ruby fails to install because `yaml` is missing, try `brew install libyaml` first.
-   If `ns doctor ios` fails because of `cocoapods` you may need to update your system's ruby version.
