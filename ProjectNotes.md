# Notes

## Note 1

`d-inline-block` forces the element to respect margin/padding while staying inline.

## Note 2

The `mb-auto` class in Bootstrap stands for "margin-bottom: auto". This class is used to automatically push the element away from the bottom of its container, but it only works if:

1. The parent container uses a flexbox layout with vertical direction (`flex-direction: column`)

2. The parent container has a set height (e.g., `height: 100vh`). Without extra space, `mb-auto` won't push the element down.

## Note 3

The CSS `inset` keyword in `box-shadow` makes the shadow appear inside the element. When two inset shadows are combined:

- First shadow: Creates a soft base layer (typically larger blur, e.g., `0.5em`)
- Second shadow: Adds sharper depth (typically smaller blur, e.g., `0.125em`)
Together they create a nuanced 3D effect.

## Note 4

 `data-bs-toggle="tooltip"`  
**Purpose**: Activates Bootstrap’s tooltip component.  
**How it works**:  
- Add to any element (button, link, etc.).  
- Tooltip content comes from `data-bs-title`(Preferred) or `title`.  
- Requires Bootstrap JS to function.  