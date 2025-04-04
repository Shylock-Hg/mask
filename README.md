
# Usage

```typst
import "@preview/mask:0.1.0": mask_str

#let masked_str =  mask_str(str: "Hello World!")
```

`masked_str` will become `************`.

To compile with mask:
```
typst compile --input mask=true main.typ
```
