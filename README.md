# File Conversion in Linux

There is a very simple file conversion utility built into Libre Office that employs the Java runtime.  The following commands will convert all files in the repo into all present types.  

    lowriter --convert-to docx doc-confluence.doc
    lowriter --convert-to docx doc-windows.doc
    lowriter --convert-to docx html-confluence.html
    lowriter --convert-to docx html-linux.html
    lowriter --convert-to docx pdf-confluence.pdf
    lowriter --convert-to docx rtf-linux.rtf

    lowriter --convert-to doc docx-windows.docx
    lowriter --convert-to doc html-confluence.html
    lowriter --convert-to doc html-linux.html
    lowriter --convert-to doc pdf-confluence.pdf
    lowriter --convert-to doc rtf-linux.rtf

    lowriter --convert-to html doc-confluence.doc
    lowriter --convert-to html doc-windows.doc
    lowriter --convert-to html docx-windows.docx
    lowriter --convert-to html pdf-confluence.pdf
    lowriter --convert-to html rtf-linux.rtf

    lowriter --convert-to pdf doc-confluence.doc
    lowriter --convert-to pdf doc-windows.doc
    lowriter --convert-to pdf docx-windows.docx
    lowriter --convert-to pdf html-confluence.html
    lowriter --convert-to pdf html-linux.html
    lowriter --convert-to pdf rtf-linux.rtf

    lowriter --convert-to rtf doc-confluence.doc
    lowriter --convert-to rtf doc-windows.doc
    lowriter --convert-to rtf docx-windows.docx
    lowriter --convert-to rtf html-confluence.html
    lowriter --convert-to rtf html-linux.html
    lowriter --convert-to rtf pdf-confluence.pdf
