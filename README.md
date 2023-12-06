# Tachidesk VaadinUI Flatpak

## Building

First, install the Freedesktop SDK and Platform:

```
 flatpak install org.freedesktop.Sdk/x86_64/23.08
```

You might need to install the Java extension as well:

```
flatpak install org.freedesktop.Sdk.Extension.openjdk17/x86_64/23.08
```

Then you can build the app

```
flatpak-builder build-dir --user --ccache --force-clean --install online.hatsune_miku.tachidesk-vaadinui.json
```

Then you can run it via the command line:

```
flatpak run online.hatsune_miku.tachidesk-vaadinui
```

or just search for the installed app on your system
