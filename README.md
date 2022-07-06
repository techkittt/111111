# 1 Overview

ComPDFKit PDF SDK is a powerful PDF library for developers to add robust PDF functionality to their applications, which ships with simple-to-use java APIs to offer document viewing, creation, searching, annotation, and editing. With this SDK, even developers with limited knowledge of PDF can quickly build a professional PDF viewer with just a few lines of code on the Android platform.



## 1.1 ComPDFKit PDF SDK

ComPDFKit PDF SDK consists of two elements as shown in the following picture.

<img src="image/ComPDFKit.png" alt="ComPDFKit" style="zoom: 25%;" />

The two elements for ComPDFKit PDF SDK:

- **PDF Core API**

  A parser for PDF documents (also known as PDF Data layer) doesn’t include any UI components. If you just need to render a PDF document without displaying any content inside the PDF, you can just integrate this into your application.

- **PDF View**

  The rendering library for PDF documents (also known as the PDF UI layer) relies on **ComPDFKit-UI.aar**. It is a visual operation logic package for page rendering, annotation operations, and form operations. You can customize page rendering and operations based on the file library.
