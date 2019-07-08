# nano
Simple container for running Nano into container distros (as RancherOS)

## Usage

```sh
$ echo 'docker run -ti --rm -v $(pwd):/nano guiscaranse/nano $@' > /usr/bin/nano && chmod +x /usr/bin/nano
```
