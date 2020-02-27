# Dockers

## Aliases to add

```
alias impacket='docker run --volume "$(pwd):/Files" -w /Files -it --rm rflathers/impacket'
alias crackmapexec='docker run --volume "$(pwd):/Files" -w /Files --rm -it local/crackmapexec crackmapexec'
alias medusa='docker run --rm -it -v $(pwd):/Files medusa'
```
