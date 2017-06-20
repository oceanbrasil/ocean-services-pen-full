# Pen SDK Full

[![Latest Stable Version](https://img.shields.io/badge/version-4.1.2-green.svg)](http://developer.samsung.com/galaxy/pen)

> Note
> 1) In the Pen SDK v4.1.0, Dynamic version is not supported, only it supports Static version.
> 2) Static version has two types, namely:
> Full Version : Supports all features of Pen SDK.
> Light version : Only supports simple drawing features of Pen SDK.

Pen SDK allows you to develop applications, such as S Note, that use handwritten input. Pen SDK uses pens, fingers or other kinds of virtual pens for input and makes it feel like you are actually writing on a notepad with various useful editing functions.

![Pen](http://developer.samsung.com/sd2_images/galaxy/content/sms_pen_150818_00.png)

With Pen SDK, creating Android applications that handle handwritten inputs is quite simple. All that needs to be done is add a view provided by Pen SDK onto the application’s layout. Through this view, inputs like pressure and speed from the S Pen are captured and processed precisely to give the realistic feel of a real pen and paper to users. Created contents such as handwritings, drawings or shapes via Pen SDK can also be edited with the various advanced editing features provided by the SDK, which can increase the satisfaction level of application users.

Pen SDK 4.x has been improved performance-wise and has added new features. The overall performance has been boosted up with the use of hardware such as NEON or GPU adaptively while reducing the power consumption. Paragraph formatting of the text box is improved to provide users with the richer ways of editing texts. And the newly added recognition engine enables the new method to add or edit various shapes without accessing the menus.

Pen SDK supports the following features:

- Advanced editing
- Recognition based shape editing
- General recognition

__Advanced Editing__

Pen SDK provides advanced ways to edit documents effectively with pens on relatively small screens. Basic objects like handwritings, drawing or shapes can be selected with a rectangle or an arbitrary shape using the lasso. Properties of the selected objects can changed with the built-in functions: group/ungroup, change z-order, color or size, etc.

![Pen 2](http://developer.samsung.com/sd2_images/galaxy/content/sms_pen_150818_01.jpg)

__Recognition Based Shape Editing__

The needs of using shapes while making contents have been there for a while to make richer documents. Limitations of the mobile environment, such as small screen size, no hardware input devices or handheld usage, still exist, but the recognition engine inside Pen SDK 4.x will automatically converts the user’s rough inputs into much refined shapes. Once shapes have been recognized and added to documents, more editing options can be applied to the added shapes, which can be compatible to those widely used word processors on PC.

![Pen 3](http://developer.samsung.com/sd2_images/galaxy/content/sms_pen_150818_02.jpg)

__General Recognition__

Pen SDK can convert input strokes into various useful data format with the built-in recognition and beautification engine. Using the text recognition, user’s handwritten texts on screen can be converted into meaningful text that can be used for searching or can be highlighted.

![Pen 4](http://developer.samsung.com/sd2_images/galaxy/content/sms_pen_150818_03.jpg)

Also, using formula recognition and shape beautification, handwritten can be converted into mathematic equations with better looking objects.

![Pen 4](http://developer.samsung.com/sd2_images/galaxy/content/sms_pen_150818_04.jpg)

__Restrictions__

Pen SDK has the following restrictions:

- Pen SDK supports devices with Android 4.0 (Ice Cream Sandwich API level 14) or higher.
- Some functions such as writing pressure or hover will be limited on the devices without the built-in S Pen.


## Download

Add into gradle project level

``` Gradle
allprojects {
  repositories {
    ...
    maven { url "https://jitpack.io" }
  }
}
```

Add into app project level

``` Gradle
dependecies{
    compile 'com.github.oceanbrasil:samsung-services-professional-audio:4.1.2'
}
```

Copyright © 2010 - 2017 SAMSUNG All rights reserved.

Portions of this page are reproduced from work created and shared by the Android Open Source Project and used according to terms described in the [Creative Commons 2.5](https://creativecommons.org/licenses/by/2.5/) Attribution License.
