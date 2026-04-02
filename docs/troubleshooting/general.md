
## std::bad_alloc {}
- Bug temporär - Stand 02.04.2026

- https://github.com/docling-project/docling-parse/issues/227
```shell
pip uninstall docling docling-parse -y
pip install "docling==2.73.1" "docling-parse==4.7.3"
```

In version 4gibt es manche features nicht mehr wie z.b.
```shell
& "$toolRoot\userbase\Python312\Scripts\docling.exe" "$toolRoot\work\input" --from pdf --to md --image-export-mode referenced --output "$toolRoot\work\output"
```

Dadurch muss man einzhelne vearbeitung
```shell
Get-ChildItem "$toolRoot\work\input" -Filter *.pdf | ForEach-Object {
    & "$toolRoot\userbase\Python312\Scripts\docling.exe" $_.FullName --from pdf --to md --image-export-mode referenced --output "$toolRoot\work\output"
}
```
