# ar-business-card
ar-business-card demo project


## AR Business Card Setup

### Marker Pattern
![AR Marker QR Code](assets/pattern-qrcode_samip-ac.github.io.png)

* **Marker Type**: QR Code
* **Marker Value**: `https://samip-ac.github.io/ar-business-card/`
* **Size Recommendation**: Print at least 8×8 cm (3×3 inches)

### How to Use
1. Print this marker or display it on a screen
2. Open the AR experience on your mobile device
3. Point your camera at the marker

```html
<!-- Corresponding code in index.html -->
<a-marker type="barcode" value="https://samip-ac.github.io/ar-business-card/">
</a-marker>
```

# DIY
## The website deployed on gitHub Pages
enable gitHub -> "pages" -> "Branch" -> "main" and "/(root)"


## Replace with your own patt marker and your own QR code
```shell
<a-marker type='pattern' url='assets/[PATT FILEPATH]'>
```


## Replace your own model on
```shell
<a-entity
    gltf-model="url(assets/[YOUR OWN MODEL])"
    scale="0.5 0.5 0.5"
    position="0 0.1 0"
    rotation="90 0 0">
</a-entity>
```
