# assorted_grapheneos_backup


- Install

```
go install github.com/github-release/github-release@latest
```

- Create a token with Repository permissions with  Read and Write access to code
- https://github.com/settings/apps

```
export GITHUB_TOKEN=github_pat_11
```

- Create a tag for release

```
github-release release --user biop0765 --repo assorted_grapheneos_backup --tag flame
```

- Run command

```
github-release upload  --user  biop0765 --repo assorted_grapheneos_backup  --tag flame --name "flame-factory-2022102300.zip.sig" --file  flame-factory-2022102300.zip.sig 
```
