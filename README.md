# MinMax Hugo Theme

A minimalist Hugo theme focused on accessibility and readability.

MinMax is an independent Hugo theme designed for users who value content, open standards, and accessibility over visual complexity and unnecessary dependencies.

## Features

* Minimalist content-focused design
* XHTML 1.0 Strict compliant markup
* HTML5-friendly structure
* Hugo 0.163+ compatibility
* Raw HTML support in Markdown content
* Semantic markup
* Accessibility-first design
* Large default typography
* Minimal CSS
* No JavaScript dependencies

## Project Goals

* Prioritize content over presentation
* Produce clean and standards-compliant markup
* Support screen readers and assistive technologies
* Improve readability for visually impaired users
* Minimize configuration and maintenance effort
* Remain compatible with modern Hugo releases

## Accessibility

Accessibility is a primary design goal.

Current accessibility features include:

* Semantic HTML structure
* 150% default font size
* 500% h1 heading size
* Minimal visual clutter
* Keyboard-friendly navigation
* Screen reader friendly markup
* High reliance on browser defaults

## Getting Started

### Install the theme

Change the current working directory to the location where you want the cloned directory. Clone the repository into your Hugo site's `themes` directory:

```bash
git clone https://github.com/denniszuther/minmax-hugo-theme
```

Alternatively, download the latest release and extract it to:

```text
themes/minmax-hugo-theme
```

### Configure Hugo

Copy the example configuration:

```bash
cp themes/minmax-hugo-theme/exampleSite/hugo.toml .
```

Adjust the configuration as needed.

### Start Hugo

```bash
hugo server
```

Open the local URL displayed by Hugo, typically:

```text
http://localhost:1313/
```

## Compatibility

MinMax is tested with:

* Hugo 0.163+
* Goldmark Markdown renderer
* XHTML 1.0 Strict validation

## Development Principles

* Semantic markup first
* Accessibility before aesthetics
* Minimal generated markup
* Minimal CSS
* No unnecessary JavaScript
* Readable source code

## Testing

Recommended validation methods:

* W3C Markup Validator
* Screen reader testing
* Keyboard-only navigation
* Text browsers such as `lynx`
* Hugo build verification

## Screenshot

[![Screenshot](https://github.com/denniszuther/minmax-hugo-theme/blob/main/images/screenshot.png)](https://github.com/denniszuther/minmax-hugo-theme/blob/main/images/screenshot.png)

## Roadmap

Future development will continue to focus on accessibility and standards compliance.

## Acknowledgements

MinMax originated from ideas explored in the accessible-minimalism Hugo theme by Leon Stafford.

## License

Released under the Unlicense.

See the LICENSE file for details.
