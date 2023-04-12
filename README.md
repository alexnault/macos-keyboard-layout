# macos-keyboard-layout

This is an **English US** keyboard layout suited for **french accents**. All dead keys are hidden behind the `Option` modifier.

![English US layout](/assets/layout.png)

When pressing the `Option` modifier, the layout becomes:

![English US layout](/assets/layout-option.png)

And then pressing a letter will produce the accentued version of it, e.g.:

```text
` + e => è
' + e => é
^ + e => ê
¨ + e => ë

and also

' + c => ç
```

## Installation

1. Clone the repo and copy `/anault.bundle` into your keyboard layouts directory:

```bash
git clone https://github.com/alexnault/macos-keyboard-layout.git ~/macos-keyboard-layout && \cp -R ~/macos-keyboard-layout/anault.bundle ~/'Library/Keyboard Layouts' && rm -rf ~/macos-keyboard-layout
```

2. Go into System Settings > Keyboard > Text Input > Edit… > + > English > anault > Add
3. Choose `anault` as your current keyboard layout from the MacOS menu bar on the top right

If at any steps the layout is not showing, simply restart your mac.

## Customizing

You can modify the source file using [Ukulele](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) to fit your needs.
