# be-undeferred [TODO]

```html
<template
    be-undeferred='{
        "on": "my-element",
        "whereMediaMatches": "..."
    }'
    defer-be-switched
    be-switched="on when..."
>
</template>
```

Need to be able to transfer the settings (MountObserver) to the enhancement as needed, because the information contained could be applicable (as it is in this case).

This applies to all enhancements.

To specify which one:


```html
<template
    be-undeferred='[
        {
            "enhKey": "be-switched",
            "mount": {
                "on": "my-element",
                "whereMediaMatches": "..."
            }
        }
    ]'
    defer-be-switched
    be-switched="on when..."
>
</template>
```
