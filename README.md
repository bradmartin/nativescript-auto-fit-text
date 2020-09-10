# AutoFitText

This plugin is based on the Nativescript Label implementation but with changes to adjust the font size according of the label's width

![Example Image](/assets/showoff.gif?raw=true)

## Installation

Describe your plugin installation steps. Ideally it would be something like:

```bash
tns plugin add nativescript-auto-fit-text
```

## Usage

### Nativescript

```xml
<Page
  xmlns="http://schemas.nativescript.org/tns.xsd"
  loaded="pageLoaded"
  class="page"
  xmlns:ui="nativescript-auto-fit-text"
>
  <StackLayout class="p-20">
    <ui:AutoFitText
      text="Testinggggggggggggggggg"
      textWrap="false"
    ></ui:AutoFitText>
  </StackLayout>
</Page>
```

## Credits

[@grantland - android-autofittextview](https://github.com/grantland/android-autofittextview)

## License

Apache License Version 2.0, January 2004
