# PoC/Regression USD files for fuzzing USD library.

At the moment, PoC/Regression files are primarily for TinyUSDZ https://github.com/syoyo/tinyusdz

No update means no PoC found, which means TinyUSDZ is stable.

## USDA

No USDA PoCs so far(as of 15th Dec, 2022), since no seg fault found in TinyUSDZ's Ascii parser.

## USDC

No USDA PoCs since 2023 Jan. TinyUSDZ's USDC(Crate binary) parser is secure and strong 💪

## USDZ

No USDZ PoCs since 2022 Sep. But may be vulnerable when it contains jpg/png, etc
(Whose are read by stb_image at the momenet, and stb_image has some security issues).

## Copus file

To be prepared.

## TODO

- [ ] Run fuzzer by enabling wuffs image loader.
