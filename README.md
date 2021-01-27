# This repository has moved.

This repository has moved to https://github.com/phlummox/hs-perl5,
where it's continuing development. Please check there for the latest developments.

## Here's the original README.md

This repository hosts a Haskell-based implementation of Perl 6.

Currently, the Pugs.hs project exists mainly for historical/archival purposes,
not for active development. (Forks are, of course, very much welcome.)

For a host of active implementations of the Perl 6 Language, please refer to
this website:

    http://perl6.org/

---

Pugs.hs is known to build with GHC 7.10.2, preferably with the Haskell Stack:

1. Install https://github.com/commercialhaskell/stack
2. `stack build --install-ghc`
3. `stack exec -- pugs`

One can also directly install it with the standard Cabal/Hackage system:

    cabal install Pugs

Please refer to the INSTALL file for further details.

---

The goal during this hiatus is to continue maintaining Pugs.hs, so it remains
installable with current and future editions of the Haskell Language, and
interoperable with current and future releases of the Perl 5 Language. :-)

Share and Enjoy!
鳳
