# nano
Simple container for running Nano into container distros (as RancherOS)

## Usage

```sh
$ echo 'docker run -ti --rm -v $(pwd):/nano guiscaranse/nano $@' | sudo tee /usr/bin/nano && sudo chmod +x /usr/bin/nano
```
