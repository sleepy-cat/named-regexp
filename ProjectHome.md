named-regexp is a thin wrapper for the standard JDK regular expressions package java.util.regex, with the single purpose of handling named capturing groups in the .net style : (?`<name>`...).

It is designed for Java 5 and newer version. [Java 7](http://blogs.sun.com/xuemingshen/entry/named_capturing_group_in_jdk7) will handle named capturing groups, so this project is not meant to last.

Some other Java regular expression libraries provide support for named captures :
  * [joni](http://github.com/jruby/joni) : regexp implementation of JRuby, very active
  * [JRegex](http://jregex.sourceforge.net/) : not updated since 2002