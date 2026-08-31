# Indian Font Conversion

Technical documentation and practical examples for understanding
Unicode and legacy Indian font systems used in typing, DTP,
publishing and printing workflows.

## Overview

Indian-language text can be encountered in two different
types of workflows:

- Modern Unicode-based text
- Legacy font-based text used by older DTP systems

These systems should not be treated as simple font changes.
In many legacy workflows, the underlying text representation
uses font-specific character mappings.

This repository documents the differences between these systems
and provides practical examples for developers, designers,
DTP operators and publishers.

## Topics Covered

- Unicode text
- Legacy Indian fonts
- Shree Lipi
- Shree Dev
- Bamini
- Kruti Dev
- Marathi typing
- Hindi typing
- Tamil typing
- DTP workflows
- Font conversion
- Character mapping
- Unicode text processing

## Who Is This Documentation For?

This reference is useful for:

- DTP operators working with legacy Indian fonts
- Hindi and Marathi publishing workflows
- Tamil DTP and Bamini users
- Designers working with older documents
- Developers handling Unicode and legacy text
- Users migrating older DTP content to Unicode

## Unicode vs Legacy Fonts

Unicode identifies characters using standardized code points,
while many older Indian font systems use font-specific
character mappings.

Because of this, simply changing a font does not necessarily
convert the underlying text.

For example, Unicode Hindi or Marathi text may need to be
converted to the appropriate legacy representation before it
can be used in an older DTP workflow.

## Shree Lipi

Shree Lipi is a legacy Indian font system encountered in
Hindi and Marathi DTP, publishing and printing workflows.

A Unicode-to-Shree-Lipi workflow generally involves:

1. Starting with Unicode Hindi or Marathi text.
2. Processing the text using the appropriate character mapping.
3. Producing the legacy representation.
4. Applying the required Shree Lipi font.
5. Using the converted text in the target DTP application.

The required font must be installed on the system for the
legacy output to display correctly.

### Online Shree Lipi Conversion Tool

For users who need to perform this conversion in a browser:

[Unicode to Shree Lipi Converter](https://unicodetoshreelipi.com/)

The online converter supports Unicode Hindi and Marathi text
and provides Unicode-to-Shree-Lipi and Shree-Lipi-to-Unicode
conversion workflows.

## Shree Dev Fonts

Shree Dev fonts are part of the legacy Shree Lipi ecosystem
and are encountered in Marathi DTP and publishing workflows.

Examples include:

- Shree Dev 0708
- Shree Dev 0714

Changing a Unicode font to a Shree Dev font does not by itself
perform text conversion. The appropriate text mapping must be
used.

## Bamini

Bamini is a legacy Tamil font system used in older Tamil
typing and DTP workflows.

Unicode Tamil text and Bamini text use different
representations. Therefore, applying a Bamini font directly
to Unicode Tamil text can produce incorrect or unreadable
output.

### Online Bamini Conversion Tool

[Unicode to Bamini Converter](https://unicodetoshreelipi.com/unicode-to-bamini-converter)

The tool provides Unicode-to-Bamini and Bamini-to-Unicode
conversion workflows for Tamil text.

## Practical Conversion Workflow

A typical legacy-font workflow can be represented as:

Unicode Text
    |
    v
Character Mapping
    |
    v
Legacy Text Representation
    |
    v
Legacy Font
    |
    v
DTP Application

The reverse workflow converts legacy text back into Unicode
for use in modern applications and web environments.

## Why Font Changing Alone Does Not Work

A font controls how characters are rendered, but a legacy
font may also rely on a font-specific character mapping.

Therefore:

Unicode Text + Legacy Font
        !=
Legacy Text Conversion

The text itself may need to be converted before the legacy
font is applied.

## DTP Applications

Legacy Indian font workflows may still be encountered in
applications such as:

- Adobe InDesign
- Adobe Photoshop
- CorelDRAW
- PageMaker
- QuarkXPress
- Printing and publishing workflows

## Example Use Cases

### Hindi and Marathi

Unicode text can be converted for legacy Shree Lipi workflows
when working with older DTP documents or production systems.

### Tamil

Unicode Tamil text can be converted for Bamini-based DTP
workflows where legacy text is required.

## Documentation

Detailed explanations and practical guides are available on site.

- [Unicode vs Legacy Fonts](https://unicodetoshreelipi.com/blog/unicode-vs-shree-lipi)
- [Shree Lipi Conversion](https://unicodetoshreelipi.com/marathi-typing-rules)
- [Bamini Conversion](https://unicodetoshreelipi.com/blog/unicode-to-bamini-converter-tamil-font-guide)
- [DTP Workflow](https://unicodetoshreelipi.com/blog/dtp-best-practices)

## Online Resources

Website:
https://unicodetoshreelipi.com/

Unicode to Shree Lipi:
https://unicodetoshreelipi.com/

Unicode to Bamini:
https://unicodetoshreelipi.com/unicode-to-bamini-converter

Unicode to Ams:
https://unicodetoshreelipi.com/ams-font-converter

## Disclaimer

This repository is intended for educational and technical
documentation purposes.

Legacy font systems may have different mappings and
implementations. Always test converted text with the exact
font and DTP workflow used by your project.
