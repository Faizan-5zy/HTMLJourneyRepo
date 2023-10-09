# PDF Embedding Techniques
This repository demonstrates different methods for embedding PDF documents into a webpage using HTML. Three common techniques are showcased: `<embed>`, `<iframe>`, and `<object>` elements. These methods allow you to seamlessly integrate PDF content into your web projects.
## Embedding Techniques
###`<embed>` Element
`<embed src="/sample.pdf" type="application/pdf" width="500" height="200">`
The `<embed>` element is used to embed external content, such as PDF files. It allows customization of width and height for display.

###`<iframe>` Element
`<iframe src="/sample.pdf" frameborder="0" width="800" height="800"></iframe>`
The `<iframe>` element is used to embed external web content, including PDF files. It supports various attributes like width, height, and frameborder.

###`<object>` Element
`<object data="/sample.pdf" width="1200" height="400" type="application/pdf"></object>`
The `<object>` element provides flexibility in embedding different types of resources, including PDFs. It supports customization of width, height, and content type.
