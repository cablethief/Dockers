# Dockers

## Tools with Dockers

### DockerHub

```
leonjza/punch-q
metasploitframework/metasploit-framework
cowrie/cowrie
cablethief/sshaft
cablethief/rpivot
```

### Github

```
docker build -t apostille https://github.com/sensepost/apostille.git
```

## Aliases to add

```
alias impacket='docker run --volume "$(pwd):/Files" -w /Files -it --rm rflathers/impacket'
alias crackmapexec='docker run --volume "$(pwd):/Files" -w /Files --rm -it local/crackmapexec crackmapexec'
alias medusa='docker run --rm -it -v $(pwd):/Files medusa'
alias testssl.sh='docker run --rm -it -v $(pwd):/Files drwetter/testssl.sh'
```
