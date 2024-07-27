# @striker1826/use-tts

`@striker1826/use-tts` is a simple TypeScript function that converts text to speech. This function uses the browser's `speechSynthesis` API to convert text to speech.

## Installation

To install this package, use npm:

```bash
npm install @striker1826/use-tts
```

## Usage

You can import the package and call the getSpeech function to convert text to speech.

```bash
import { getSpeech } from '@striker1826/use-tts';

getSpeech('Hello!');
```

## Function Description

```bash
getSpeech(text: string): void
```

Converts the given text to speech.

## Parameters

text: string - The text to be converted to speech.

## Browser Compatibility

This function only works in a browser environment. It does not work in a Node.js environment because there is no window object and speechSynthesis API.

## Contribution

Contributions are welcome! If you find any bugs or have feature requests, please submit an issue.

## License

This project is distributed under the MIT License. For more details, refer to the LICENSE file.
