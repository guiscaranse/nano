# nano
Simple container for running Nano into container distros (as RancherOS)

## Usage

If you need nano available globally you can use:

```sh
$ echo 'docker run -ti --rm -v $(pwd):/nano guiscaranse/nano $@' | sudo tee /usr/bin/nano && sudo chmod +x /usr/bin/nano
```
But we recommend you to use:

```sh
$ echo 'function nano () {(docker run -ti --rm -v $(pwd):/nano guiscaranse/nano $@)}' | tee -a ~/.profile
```
