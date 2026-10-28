# J M Rajan (Knieoc Layout)

A reconstructed Keyman keyboard intended for **legacy-encoded Tamil Ka fonts**, based on observed behavior of the older Knieoc Typewriter keyboard. This is an independent reconstruction, **not** an official Knieoc release.

## Install

1. Install [Keyman](https://keyman.com/).
2. Download `jmrajan_typewriter.kmp` from the **Releases** section of this repository.
3. Open the `.kmp` file with Keyman and select **J M Rajan (Knieoc Layout)**.
4. In Microsoft Word choose a compatible legacy Ka Tamil font. Standard Unicode Tamil fonts and keyboard layouts are not equivalent.

## Source and building

- `jmrajan_typewriter.kmn`: editable keyboard source
- `jmrajan_typewriter.kps`: package definition
- `observed_mappings_v3.csv`: mapping observations

With Keyman's `kmc` compiler installed, run `kmc build jmrajan_typewriter.kmn` followed by `kmc build jmrajan_typewriter.kps`. The latter produces `jmrajan_typewriter.kmp`. The compiled `.kmx` is generated locally and need not be committed.

## Compatibility and caveats

Tested by the keyboard's user on macOS with Keyman as an earlier version of this reconstruction. **The updated display name requires recompiling and testing this package.** Windows compatibility has not yet been independently confirmed. This is a behavioral reconstruction from captured keystrokes, not an original-source recovery or complete decompilation. Longer untested sequences may differ from the original.

## Attribution and redistribution

This layout is based on the legacy Knieoc Typewriter keyboard. The original author and license have not been verified; this repository does not claim to be the original Knieoc software or include its binary or proprietary Ka font files. No open-source license is asserted for the reconstructed layout pending rights review.
