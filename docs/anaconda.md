[back to home](../README.md)

# Install Python using Anaconda distribution

Anaconda is a free Python distribution. You can download Anaconda from
[download page](https://www.continuum.io/downloads). Follow the
instruction after the download. Basically, you can use
command-line to install downloaded Anaconda as follows.

```bash
bash Anaconda2-4.0.0-MacOSX-x86_64.sh
```

Then, you can add unpacked path to `.bash_profile`
(which they automatically put that for you)

## Update Anaconda

We can update Anaconda once in a while, here is command for an update

```bash
conda update conda
```

This is when there is failed SSL, we have to set `ssl_verify` to `False`

```bash
conda config --set ssl_verify False
```
