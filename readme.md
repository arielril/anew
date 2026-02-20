# ANEW - Append New Lines to files

Append only new lines from stdin. If lines from input are already present in the original file, 
nothing is done. 

This tool works exactly as using `tee -a`: new lines are appended to the file and written to stdout.

## Install

```shell
cargo install aanew
```

## Usage

```sh
echo "a new line to append" | anew my-old-file-without-the-new-line
```
