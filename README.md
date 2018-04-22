<h1 align=center>Knowledge</h1>
<p  align=center>List of stuff I have learnt...</p>

## CLI

### Capture screenshots automatically <kbd>OSX</kbd>

```sh
i=1; while true; do screencapture -C -m -t jpg -x ~/captures/$i.jpg; let i++; sleep 1; done
```

### Grep same file in multiple directory <kbd>\*nix</kbd> <kbd>OSX</kbd>

```sh
find . -maxdepth 2 -name package.json -exec grep --color -niH 'node ' {} \;
```

### Execute specific chef-solo recipes <kbd>\*nix</kbd> <kbd>OSX</kbd>

```sh
sudo chef-solo --config-option cookbook_path=`pwd` -o apache2::default,apache2::vhosts
```
