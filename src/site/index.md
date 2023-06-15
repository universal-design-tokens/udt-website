---
title: Universal Design Tokens
layout: html.njk
---
The Universal Design Tokens (UDT) project aims to provide a suite of JavaScript libraries that simplify supporting the [Design Tokens Community Group (DTCG) file format](https://tr.designtokens.org/format/) in your applications.

UDT libraries handle the lower level concerns like parsing and serialising DTCG files, and let you access and manipulate design token data via a higher-level API called the Token Object Model (TOM).

## Current status

UDT is still under development and has not yet made an initial release. You can browse the work-in-progress code in the [UDT GitHub repo](https://github.com/universal-design-tokens/udt).

Please be aware that UDT is currently a hobby project of [James Nash](https://cirrus.twiddles.com/), so progress is slow and sporadic. Feedback, ideas and contributions are welcome. If UDT's vision excites you, please get involved! However, if you're looking to add support for DTCG files in your app _right now_, you'll need to look elsewhere for the time being.

## Wasn't UDT going to be a file format?

Originally, yes. However this is no longer the case. When James Nash started the UDT project in 2018, the [Design Tokens Community Group](https://www.designtokens.org/) did not yet exist. The [UDT project's original aim](/original-plan/) was therefore to [specify a standard file format for design tokens](https://github.com/universal-design-tokens/udt/blob/legacy-udt-libs/packages/spec/docs/README.md) and provide libraries for working with those files. When the DTCG was formed in 2019 and James joined the group as one the format editors, creating a separate UDT file format became redundant. This project therefore pivoted to its new aim of building a suite of libaries that simplify working with DTCG files. 
