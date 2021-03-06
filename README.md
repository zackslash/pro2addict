# Pro 2 Addict
A command-line tool written in Go; that converts MIDI drum tracks from Guitar Pro 6 to Addictive Drums 2.

### Pre-built Downloads

[Windows](https://drive.google.com/open?id=0BxVgyPt7oHs5azFuSG5uNk5Hc1U)

[Mac](https://drive.google.com/open?id=0BxVgyPt7oHs5ajRPeE1qWklGRFE)

[Linux](https://drive.google.com/open?id=0BxVgyPt7oHs5MTJjWVAxTXVMcDA)

### Usage
```bash
usage: pro2addict [<flags>] <in> [<out>]
Example : ./pro2addict great_drums.mid ./great_drums_ad2.mid

Flags:
  --help     Show context-sensitive help (also try --help-long and --help-man).
  --version  Show application version.

Args:
  <in>     location of your Guitar Pro MIDI file
 [<out>]  location to output converted (AD2) MIDI file (If no output is specified the result will be output to the same directory and filename as the original, appended with "-ad2.mid"
```

## Build
Source will compile under Go 1.x. [Glide](https://glide.sh/) has been used for package management.

## License
Pro2addict is released under the MIT License.
See the bundled [LICENSE](https://github.com/zackslash/pro2addict/blob/master/LICENCE) file for details.
