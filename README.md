# watermark-print-dynamic-js
an HTML, CSS and JavaScript code for getting a watermark at windows print mode, and the watermark is getting diagonally and dynamically on each page. The watermark is created dyanamically on print event of JavaScript, when the header section is not available for &lt;style> components and thus creating the watermark and its body dyanamically in JS

`Demo`   <a href="https://millstack.github.io/watermark-print-dynamic-js/" target="_blank" style="text-decoration: none;" >Watermark demo site</a>   

<br/>

`Text Watermark`   
``` html
<button id="btnPrint" type="button" onclick="printDiv('divPrint', 'text');">Print</button>
```   
<br/>

`Image Watermark`   
``` html
<button id="btnPrint" type="button" onclick="printDiv('divPrint', 'img');">Print</button>
```   

