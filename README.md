# Android-Javascriptinterface


Welcome to the Android-Javascriptinterface example!

This application shows how to create a JavascriptInterface to communicate between a web page and an Android application.


The html code :

`<body onload="onload();">`
`<script type="text/javascript">`
    `var textbox;`
    `function onload() { `
        `textbox = document.getElementById('textbox');`
    `}`

    `function showAndroidToast(toast) {`
        `Android.showToast(textbox.value);`
    `}`
`</script>`

`<div id="inner">`
`<input type="text" name="enter" class="enter" placeholder="Write something here!" id="textbox"/>`
`<input type="button" value="Send message to android!" onClick="showAndroidToast()" />`
`</div>`


![](https://i.stack.imgur.com/qiwaW.png)
