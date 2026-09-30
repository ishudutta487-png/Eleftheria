# Language system

## Purpose

Multilingual access helps readers use the interface in a comfortable or native language and helps contributors’ ideas reach beyond a single language audience.

## UI locale and content language

- **UI locale:** the language used for interface text, including navigation and controls.
- **Content language:** the original language of an individual piece of content.

These are separate choices. A visitor may browse an English interface while reading content in another language.

## Example locale architecture

Maintain interface strings by locale, for example: `locales/en/`, `locales/hi/`, and `locales/ar/`. This is an illustrative organisation, not a list of promised supported languages. Content records should identify their original language and any translation or adaptation available.

## Translation principles

- Preserve the contributor’s meaning and context.
- Credit translators and adapters.
- Label translated and adapted material clearly.
- Do not treat one language as inherently more authoritative than another.

## UX requirements

- Make language selection visible and understandable.
- Display native language names where appropriate.
- Support script rendering and right-to-left layouts when relevant.
- Keep the selected interface language consistent through navigation where possible.

## Missing translations

When a translation is unavailable, retain access to the original-language content, state the available language clearly, and avoid blank or broken interface states.
