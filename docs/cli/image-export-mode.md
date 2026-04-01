
# Single file

## Export images to external files and seperate from md file
```shell
docling knowledge\pms\dampsoft\DS_Anleitung_Smartphone_Anbindung.pdf --to md --image-export-mode referenced
```



# Multiple files

## Recursive folder
```shell
cd C:\shared\sandbox-toolchains\python-general\work
docling input --to md --image-export-mode referenced --output output
```

### 1 page-batch-size 1
```shell
cd C:\shared\sandbox-toolchains\python-general\work
docling input --to md --page-batch-size 1 --image-export-mode referenced --output output
```
