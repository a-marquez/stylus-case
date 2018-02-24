CASE
---
*Safety first, Cooper*

## Intro
- small stylus api
- includes minimal and useful class utilities, can be required all at once or piecemeal
- ideal base for prototyping or full projects
- inspirations: nib, kouto-swiss, milligram

## Installation
```sh
$ npm install a-marquez/stylus-case
```

## Usage
**Importing whole**
```stylus
@require 'case'
```

**Importing section**
```stylus
@require 'case/display'
```

**Compilation**
```sh
$ stylus main.styl --use stylus-case
```

## Philosophy
- reusability
- low specificity (shallow nesting)
- clarity - obvious class names anyone can start working with, minimal shorthands
  - conscious tradeoff of legibility over convenience
