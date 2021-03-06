JFreePDF
========

Version 2.0, by David Gilbert, 1 March 2020.

(C)opyright 2013-2020, by Object Refinery Limited.  All rights reserved.

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.jfree/org.jfree.pdf/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.jfree/org.jfree.pdf)

Overview
--------
JFreePDF is a library module for the Java(tm) platform that allows you to create content in Adobe's Portable Document Format (PDF) using the standard Java2D drawing API (`Graphics2D`).  JFreePDF is light-weight, fast, and has no dependencies other than the Java runtime (11 or later).  The home page for the project is:

http://www.object-refinery.com/orsonpdf/

Getting Started
---------------
The Javadoc page for the `PDFDocument` class gives an example of typical usage.

Oracle provides tutorials for Java2D here:

http://docs.oracle.com/javase/tutorial/2d/

There are some demonstration applications included in the [JFree Demos](https://github.com/jfree/jfree-demos) project. 


Include
-------
JFreePDF is published to the Central Repository. You can include it in your projects with the following dependency:

    <dependency>
        <groupId>org.jfree</groupId>
        <artifactId>org.jfree.pdf</artifactId>
        <version>2.0</version>
    </dependency>

JFreePDF defines the module name `org.jfree.pdf`.

If you are using Java 8, an earlier version of this library (OrsonPDF) can be used instead:

    <!-- https://mvnrepository.com/artifact/com.orsonpdf/orsonpdf -->
    <dependency>
        <groupId>com.orsonpdf</groupId>
        <artifactId>orsonpdf</artifactId>
        <version>1.9</version>
    </dependency>

Build
-----
You can build JFreePDF from sources using Maven:

    mvn clean install


Dual Licensing
--------------
JFreePDF is dual licensed.  You can use JFreePDF under the terms of the GNU General Public License version 3 (GPLv3) or later.  If you prefer not to be bound by the terms of the GPLv3, there is an option to buy a commercial license from Object Refinery Limited.

JFreePDF integrates the `Ascii85OutputStream` class written by Ben Upsavs and distributed freely under the (BSD-style) terms listed in the `Ascii85OutputStream-license.txt file`.


Change History
--------------

Version 2.0 (1 March 2020)

- converted to a Java module;
- renamed `OrsonPDF` to `JFreePDF`.
