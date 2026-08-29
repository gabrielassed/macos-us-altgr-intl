# macos-us-altgr-intl

## Motivation

[US International (with AltGr dead-keys) on macOS](https://carjorvaz.com/posts/us-international-with-altgr-dead-keys-on-macos/)

## Installation

```
sudo cp us-altgr-intl.keylayout /Library/Keyboard\ Layouts
```

You'll need to reboot for the new layout to appear in System Settings.

Tested to be working on macOS Tahoe 26.2.

## Modifications from this fork

- Update layout name to "English (intl. with Option dead keys)" (just to look nice in the layout selector);
- Added ordinal indicators: Option + F produces ª (feminine), and Option + G produces º (masculine);
- Completed uppercase vowel composition for acute, grave, tilde, circumflex,
  and diaeresis dead keys;
- Made the Option layer Caps Lock aware while preserving its dead keys and
  symbols;
- Added symmetric uppercase cedilla composition.

## Acknowledgments

- [US International on OS X](https://www.twam.info/hardware/us-international-on-os-x)
- [osx-us-altgr-intl](https://github.com/xv0x7c0/osx-us-altgr-intl)
- [Ukelele](https://software.sil.org/ukelele/)
