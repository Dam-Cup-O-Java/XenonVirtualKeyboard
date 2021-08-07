# XenonKeyboard
![GitHub license](https://img.shields.io/badge/license-MIT-lightgrey) ![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FLord-Xenon%2FKeyboardIntegration)

Xenon keyboard can make your life easy.

## Adding Script and stylesheet
Add script and the stylesheets below in ```<head></head>``` of your website for the keyboard to work

```diff
    <script defer src="https://keyboard-integration.vercel.app/keyboard/Keyboard.js"></script>
    <link rel="stylesheet" href="https://keyboard-integration.vercel.app/keyboard/Keyboard.css">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
```

## Integration
Add ```class="use-keyboard-input"``` in the textarea for which you want the virtual keyboard

```
<textarea class="use-keyboard-input"></textarea>
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
