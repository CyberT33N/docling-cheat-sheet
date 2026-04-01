Windows

Check versions
```shell
pyenv versions
```

Set global version:
```shell
pyenv global 3.9.13
```

Install:
```shell
pip install docling
pip install hf_xet
```

Test:
```shell
docling https://arxiv.org/pdf/2206.01062
```



# Troubleshooting

## Der Befehl "docling" ist entweder falsch geschrieben oder konnte nicht gefunden werden.

 PATH fixen

Füge das hinzu:
```shell
$env:PATH += ";C:\Users\denni\AppData\Roaming\Python\Python313\Scripts"
```

Dauerhaft:

```shell
setx PATH "$env:PATH;C:\Users\denni\AppData\Roaming\Python\Python313\Scripts"
```

Danach neues Terminal öffnen.
