Float Labeled EditText
==============

Simple implementation of a Float Labeled EditText: An Android view which uses a EditText and puts the hint on top of the EditText when it is populated with text. 

iOS implementation by [@jverdi](http://www.twitter.com/jverdi): [JVFloatLabeledTextField](https://github.com/jverdi/JVFloatLabeledTextField) 

Credits for the concept to Matt D. Smith ([@mds](http://www.twitter.com/mds)).

![Android Version](http://i.imgur.com/ucRd1jm.gif)

http://dribbble.com/shots/1254439--GIF-Mobile-Form-Interaction?list=users


Usage
=====

Add the library project or grab to build.gradle:
```groovy
compile 'com.wrapp.floatlabelededittext:library:0.0.4'
```
or plain maven:
```maven
<dependency>
  <groupId>com.wrapp.floatlabelededittext</groupId>
  <artifactId>library</artifactId>
  <version>0.0.4</version>
  <type>aar</type>
</dependency>
```
and then insert the view in XML:

```xml
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:float="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">

    <com.wrapp.floatlabelededittext.FloatLabeledEditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        float:fletFloatingHint="Username"/>

    <com.wrapp.floatlabelededittext.FloatLabeledEditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        float:fletFloatingHint="Password"
        float:fletInputType="textPassword"/>
</LinearLayout>
```
Developed By
============

* Henrik Sandström [@heinrisch](https://twitter.com/Heinrisch)
* Aaron Rietschlin [@AaronRietschlin](https://twitter.com/AaronRietschlin)

Styled By
=========

* Marcus Gellemark [Dribbble](http://dribbble.com/Gellermark)

Additional Credit
=================

* Quentin DOMMERC [dommerq](https://github.com/dommerq)

Notes
=====
It would be much better to extend EditText and implement this functionallity...


License
=======
This project is licensed under the MIT License:

Copyright (c) 2012 Bohemian Wrappsody AB

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
