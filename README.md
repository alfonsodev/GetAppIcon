# GetAppIcon

Get App icons by pid on macOS. Returns a `base64` encoded data string which can be used for displaying or manipulating the resulting image.

## Usage

```bash
$ swift build -c release
```

```bash
$ .build/release/GetAppIcon --help
Usage:

    $ .build/release/GetAppIcon <pid>

Arguments:

    pid - pid of the Application

Options:
    --size [default: 32] - Size of out the output
```

## Example

```bash
$ .build/release/GetAppIcon 814 --size 512
data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAA...
```
