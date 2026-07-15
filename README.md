[English](README.md) | [Български](README.🇧🇬.md) | [Українська](README.🇺🇦.md) | [Čeština](README.🇨🇿.md)

# BRT – Browser Reader Mode Compatibility Test

## Web Content Accessibility Test

## Website

🌐 Website:
https://vesosoft.github.io/BRT/

📚 Documentation:
docs/

🧪 Test Cases:
docs/test-cases/

BRT (Browser Reader Mode Compatibility Test) is a public, unofficial methodology for quickly checking whether a website is comfortable to read using browser accessibility features.

The goal is to allow anyone, without technical knowledge, to check whether the main content of a website remains accessible and readable.

## Why is BRT needed?

Many people use accessibility features such as:

- Reader Mode / Reader View
- text enlargement
- contrast adjustment
- dark mode
- other settings for easier reading

When a website does not work well with these features, some users may lose access to its content.

## What does BRT check?

BRT checks:

- whether the main text is extracted correctly;
- whether the complete article is displayed;
- whether distracting elements are removed;
- whether the text can be read comfortably;
- whether there are problems with images and additional content.

## Tested browsers

BRT testing can be performed using different browsers with accessibility features.

Current test environments:

- Google Chrome — Reader Mode tested
- Mozilla Firefox — Reader View tested
- Microsoft Edge — accessibility features tested; Reader Mode availability depends on page and version
- Opera — accessibility features tested; Reader Mode availability depends on page and version

## Important note

BRT evaluates compatibility with browser Reader Mode / Reader View features.

It does not replace complete web accessibility testing standards such as WCAG.

## Documentation

Full methodology:

`docs/brt.html`

## Real-world test cases

BRT includes documented accessibility tests performed on real websites.

Examples:

- Test #001 - Meteo Balkans  
  Reader Mode can be activated, but the main content extraction fails.

- Test #002 - Miele  
  Chrome Reader Mode works. Firefox Reader View is not available.

## Principle

BRT is not a tool for criticizing websites.

It is a tool for identifying barriers for readers and improving the accessibility of web content.

## Versions

### BRT 1.1

Second version:

- moved website files to the `/docs` directory;
- improved project structure;
- separated documentation from website content;
- improved multilingual documentation support.

### BRT 1.0

Initial methodology version:

- Reader Mode test;
- PASS / PARTIAL / FAIL criteria;
- manual testing methodology.

## Participation

Everyone can help:

- test websites;
- suggest improvements;
- report problems;
- contribute to the development of the methodology.

## License

This project was created as a public initiative to improve web content accessibility.

BRT is not an official standard or certification system. It is a practical testing methodology.

## Status

Current version: BRT 1.1

Status: Current working version

## Author

Created by Veselin Ignatov
