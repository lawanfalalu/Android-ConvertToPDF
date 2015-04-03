# Using [iText]

To use the library.
  - The project is "/ConvertToPdf-iText/"
  - Download Jar file from http://sourceforge.net/projects/itext/files/latest/download?source=files
  - Add it to your "lib" folder (with Android-Studio, you may need to right-click the lib/itextpdf-x.x.x.jar -> "Add as Library...")
  - Add permission to your AndroidManifest
  
```xml
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
```

# Using Aspose
  - The project is "/ConvertToPdf-Aspose/"
  - Download Aspose zip from http://www.aspose.com/community/files/74/android-components/aspose.pdf-for-android/default.aspx
  - When you extract you'find:
    - "Aspose.Words.zip" offers the feature to [convert word files to PDF]. For further details, please check Convert word file to PDF Furthermore, it supports variety of document formats i.e. DOC, DOCX, ODT, RTF, EPUB etc. Please check [Supported file formats for more information].
    - "Aspose.Cells.zip" offers the feature to [convert Excel worksheets to PDF]. For further details, please visit Convert Excel files to PDf please check
    - "Aspose.Slides.zip" offers the feature to [convert PowerPoint presentations to PDF]. For further details, please check Convert Presentations to PDf
    - "Aspose.Pdf.zip" offers the feature to convert Text, Image, HTML, XML files to Pdf format.
  - Add "Aspose.Pdf.Android-x.X.jar" to your "lib" folder (with Android-Studio, you may need to right-click the lib/itextpdf-x.x.x.jar -> "Add as Library...")
  - Add permission to your AndroidManifest
  
```xml
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
```
  

  
  
  
  
[iText]: http://itextpdf.com
[convert word files to PDF]: http://www.aspose.com/docs/display/wordsjava/How+to++Convert+a+Document+to+PDF
[Supported file formats for more information]: http://www.aspose.com/docs/display/wordsjava/File+Formats+and+Conversions
[convert Excel worksheets to PDF]: http://www.aspose.com/docs/display/cellsjava/Converting+to+PDF+Files
[convert PowerPoint presentations to PDF]: http://www.aspose.com/docs/display/slidesjava/Converting+to+PDF+File
