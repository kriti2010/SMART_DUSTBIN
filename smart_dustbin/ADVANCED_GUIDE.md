# Advanced Guide

## Customization

You can customize the 3D prototype by opening `smart_dustbin_prototype.html` in any text editor.

### Changing Colors
Look for the material definitions in the `<script>` tag. You can modify the hex color codes:
```javascript
const bodyColor = 0x222222;
const lidColor = 0x444444;
const organicColor = 0x4CAF50;
const plasticColor = 0x2196F3;
```

### Modifying the Sorting Logic
The `sortWaste()` function handles the sorting animation. You can change the target positions to customize which compartment specific waste items go to.
