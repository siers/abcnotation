
# abcnotation

A Haskell representation and parser for ABC notation 2.1.

ABC notation is a text-based music notation system designed to be comprehensible by
both people and computers. For more information see <http://abcnotation.com>.

## Limitations

  * Limited support for *volatile* features
  * Limited support for text strings (§8.2)
    * No mnemonics
    * No entities
    * Unicode escapes are supported
  * No support for macros (§9)
  * No support for outdated syntax (§10)
  * Stylesheet directives are ignored (§11)
  * Typeset text is ignored (§2.2.3)
  * Strict interpretation assumed (§12)


## Requirements

* [Haskell Platform](http://www.haskell.org/platform)

## Installation

    cabal configure
    cabal install
