# journal

## Shell alias

### vimj

The `vimj` is used to open a file based on date.


```shell
alias vimj="vim $(date +'%Y%m%d').md"
```

### gitj

The `gitj` is used to commit staged files with default message based on date.

```shell
alias gitj="git commit -m \"annotations from $(date +'%Y-%m-%d %H:%M')\""
```

