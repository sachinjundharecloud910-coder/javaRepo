# HTML to PDF with iText in Java

This example demonstrates how to convert HTML content to PDF using the **iText 7** library in Java.

## Features:

- Converts a **hardcoded HTML string** into PDF (`string-to-pdf.pdf`)
- Converts a **styled external HTML file** (`index.html + style.css`) into PDF (`index-to-pdf.pdf`)
- Uses `HtmlConverter` from `iText pdfHTML`

## Folder Contents

| File : Purpose |

| `App.java` | Java code for conversion |
| `index.html` | HTML template for PDF |
| `style.css` | Styling applied to the PDF |
| `java.png` | Image used inside the HTML (optional) |

## How to Run

1. Ensure you have **Java 8+** and **iText 7 libraries** (`html2pdf` JARs)
2. Compile and run the project:

```bash
javac -cp "itext7-core.jar" com/hmkcode/App.java
java -cp ".;itext7-core.jar" com.hmkcode.App
