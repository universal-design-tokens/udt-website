---
title: Universal Design Tokens
layout: html.njk
---
## What is this?

Universal Design Tokens (UDT) is an open-standard file format for expressing design token data.

The UDT project is only just starting out, so at this point we're mainly looking for feedback and contributors. Visit the [UDT GitHub organisation](https://github.com/universal-design-tokens) to get involved!

## What problem does it solve?

With the rise of design systems several tools that export, convert or import design token data have been created. Unfortunately, each one uses its own, custom format for expressing that design token data. This limits interoperability between such tools and creates additional work for those wishing to integrate them into their design systems.

While most existing tools use simple, self-explanatory JSON or YAML-based formats, the structure of the data within those files is nonetheless custom. Documentation of those file formats are frequently limited or absent completely. This means that others wishing to connect different tools, generate data or process data need to reverse engineer those formats and write their own bespoke code to work with it.

Wouldn't it be great if all those tools shared the same file format for design token data? Different tools could then easily be connected in new and interesting ways simply by taking files saved by one and loading them into another. Life would also become easier for developers and companies wishing to make new tools that do interesting things with design token data since they could focus on the tool itself and simply reuse the existing file format.

We could stop reinventing wheels and spend more time designing and building cool things.

After all, isn't that part of the ethos that underpins all design systems?

This [UDT presentation](https://www.slideshare.net/c1rrus/universal-design-tokens) provides some additional background about this project.

## How will it work?

At its core, Universal Design Tokens will be a format specification and schema. The goal is to document exactly how UDT files are formatted, and how parsers and serialisers should behave.

The current plan (which is subject to change) is for UDT files to be [JSON files](https://www.json.org/) with a well-defined structure that will be specified by a [JSON Schema](http://json-schema.org/). If you'd like to get involved, head over to the [spec repo](https://github.com/universal-design-tokens/udt/tree/master/packages/spec) on GitHub.

In parallel, a reference implementation of a software library for parsing and seralising UDT files will be developed in JavaScript. Visit the [lib repo](https://github.com/universal-design-tokens/udt/tree/master/packages/lib) on GitHub to find out more and get involved.

We hope that a clear spec and a working implementation will inspire others to build an eco-system of tools and software libraries that interchange UDT files and enable design system makers to do incredible things!
