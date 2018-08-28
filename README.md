# gallery-js
Photo Gallery likes Facebook Friendship's Day

## How to use

### JS
```js
var photos = [
    {
        src: 'https://lh3.googleusercontent.com/Jn2iGlvBs_xXo4Wv8RtMiAXvRefy55ogjEuEd64Ru1MEJjFjBc0hGBdW_1WfOME7tGP7NduUPQgwMjvG1useyNP9XvH3w3AHm4ZW_tU0o8Pn-1tmOpoAt2E7T0r3HprbB8ZCCb03biuPJne332ZyLNIrCDbw1kr_LVTV-PpT2Hdg54rOz05mYteX8OlJz86vFfcRwqESnIhixdkWBH1WamsjrMKV2WJnYXuDPX91nGAhdzDWoxWg2cbPSg6ZAqGhQm35K9fwCTEePOrkYdYW5d-JLSYpRttsGEUiJ0pzsdvFpMaxvij2Rpp3XkSQPqWzSKLCGio7VEw_ZpLZUjvmXYjscKgDqKzo-VfdLdsM8NhVOOKsyOiUugxcAYsWQWc_VZOkQmWfqGSLTYdbpTcTHwL7n7qvCpciVnxx661_d2GYfYZKdiJqKGXyWkUnLHSoUEQ_F32PlSZu4WI8EAOMC6HFQxeOf02Wz5KjAUqCzZzfA9jMvWtWWaneUFfvu6sTFZ3KE_0oVgE8aU8OxYFvkYc00ee84Za3x8EWR8B8l-uyQ2YxIfmYiTIx4BKgIx3C8kKPboZ40RAG5aoyOp1G_1oA7q9lXvdV7lqQaPqbqQMTWtbARa0Z33_jTR9VWdjHt-fd4du5OYXnTHINEdJWa5EkQPOjnj-KDU3sZrwAlw3lm4tJ-n0GEXOv=w718-h404-no',
        title: 'Trinh Mập'
    }, {
        src: 'https://lh3.googleusercontent.com/vOWnkgO2tUZth879we0sAQR2mkzP6iihTcWKe7bG6Zx8ah4yt7cWvL_24CNwwgMVu8b98iZ_mIElGg3pUQpz9Xrq4bK6tfBwv_8dNmlzhWA1TQWAG30DwbVYfo43_5oaNEAlmNFXRpsnWno4mx5lr0N3j_vR9B-k6AtuOO5kGHB25NG7DFrqo6zYwZN2VsbuYrqdkZKhTbdux7YhdQdwx9fs1Fxr9soWNToP-TFH1hGeuJ8PDYPtwCV6T2OfdS6EYgUDzvLn2EaGrMEv3mXk7Z_06Wkxz3Q2Ea5GKvGO3nxT-egmMEtlnSbW6_XEptrtjR6lHG6gtHRT626V2-r-PqyWKc4eLidqkeYySoimmpJjxYmdetb_20sscXFLhxcsPuBRYyWgjv-lXzxLj8K7UpsmhOVK6ZvzAREwXV1a3ESzn8bnOg0eVojjCfJm4LeubbwFamzHb-DbBvqbdBiSP17ZoLXqTxgKn4rEqeaiWL-YIsrgwaI2K9iy0okeOSmzQuesWbTzZzg7TDAkURt1CjDXa74K2yfM-WRtyygfqXiuwTQSqo_-wH1l5A7VLo9sWiNK6q040-6QW-V0GcxttqNI2zD5NtU7iGQOs6yc9omPU9Lhe_Wbt1YN31Heha7fRrpRfsJpHKi9kDIy47_OhkTEyGp2pHhEGrWL4BTO8uG9v8NmLJCaUDRE=w2592-h1944-no',
        title: 'Bỏ nhà đi lang'
    }
];

var gallery = new Gallery('root', 3000, photos);
```

### HTML
```html
<html>
    <head>
        <link rel="stylesheet" href="../gallery.css">
    </head>
    <body>
        <div id="root"></div>
        <script src="../gallery.js"></script>
    </body>
</html>
```
