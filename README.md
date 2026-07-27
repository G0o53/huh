# huh?
![Static Badge](https://img.shields.io/badge/license-MIT-blue)

![huh GIF](demo.gif)

`huh` is the blazing fast package manager for [`YOM`](https://github.com/G0o53/yom). To install, make sure you're on a UNIX-like OS and do
```bash
curl -fsSL https://raw.githubusercontent.com/G0o53/huh/refs/heads/master/huh.install | sh
```

To install using `huh`, just say to the terminal 
```bash
huh <username>/<repo>
```
and it will fetch it, it installs to `~/.huh/`.

If you're looking for a way to make a `huh` package, have no fear! First publish to GitHub,
then just add a file, `BUILD.box`, and populate it with a shell script to compile your package,
make sure that puts the finished product into the `PKGINSTALL` directory (pre-created by `huh`),
it will then be installed into the default folder.

_if you like this, give it a 🌟_
