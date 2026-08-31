# Unicode vs Legacy Indian Fonts

## Introduction

Unicode and legacy Indian font systems represent text in
different ways.

Unicode is designed to represent characters independently of
a particular font. Legacy Indian font systems may instead use
font-specific character mappings that were designed for older
DTP and typing environments.

This distinction is important when moving text between modern
web applications and older publishing workflows.

## Unicode

Unicode assigns standardized code points to characters.

For example, Hindi and Marathi characters can be stored as
Unicode text and used across websites, databases, operating
systems and modern applications.

The same Unicode text can normally be rendered using different
Unicode-compatible fonts without changing the underlying text.

## Legacy Font Systems

Older Indian-language DTP workflows may use font-specific
character mappings.

In these systems, the text representation and the font are
closely connected.

This means that changing a font does not necessarily convert
the text from one encoding system to another.

## Why Incorrect Characters Appear

Suppose a Unicode Hindi string is copied into an application
that expects a legacy Shree Lipi representation.

Applying a legacy font directly may produce incorrect
characters because the underlying text is still Unicode.

The correct workflow is to convert the text representation
before applying the required legacy font.

## Typical Workflow

Unicode Hindi/Marathi
        |
        v
Conversion / Character Mapping
        |
        v
Legacy Representation
        |
        v
Shree Lipi / Shree Dev Font
        |
        v
DTP Application

## Reverse Conversion

The same concept applies when old DTP content needs to be
migrated into modern Unicode-based applications.

Legacy representation
        |
        v
Character Mapping
        |
        v
Unicode
        |
        v
Modern Applications / Web

## Shree Lipi

Shree Lipi is encountered in legacy Hindi and Marathi DTP
workflows.

Related fonts can include Shree Dev variants such as Shree Dev
0708 and Shree Dev 0714.

Online conversion resource:

https://unicodetoshreelipi.com/

## Bamini

Bamini is a legacy Tamil font system.

Unicode Tamil text should not simply be displayed by changing
the font to Bamini. A suitable conversion process is required
when legacy Bamini text is expected.

Online conversion resource:

https://unicodetoshreelipi.com/unicode-to-bamini-converter

## Key Point

Changing the font and converting the text are two different
operations.

Font selection controls rendering.

Text conversion changes the underlying representation.

Keeping these two concepts separate helps avoid many common
Indian-language DTP and migration problems.
