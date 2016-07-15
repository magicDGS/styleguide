Style Guides for magicDGS projects
==================================

This repository contains style guides for code in my projects, to facilitate
formatting with different IDEs for contributors and to maintain consistency in
my code.


They are based in the [Google Style Guide](https://google.github.io/styleguide/javaguide.html)
for Java, with the following changes (mandatory):

* Blocks of non-static imports ordering:
  1. `org.magicdgs.*`
  2. other packages in alphabetical order
  3. `java.*` and `javax.*`
* Indentation:
  - +4 spaces for new blocks
  - Double spacing for continuation blocks
  - No alignment in multi-line statements
* Line-wrapping:
  - Enum constants are always wrapped
  - Annotations are always wrapped, but not the parameters even if they exceed the line limit
* Javadoc:
  - At-clauses descriptions are aligned
  - Blank lines after description, @param and @return

## SETTING UP IDE

* IntelliJ
  - Go to "Preferences" -> "Coding Style".
  - Import [intellij-java-magicdgs-style.xml](https://github.com/magicDGS/styleguide/blob/master/intellij-java-magicdgs-style.xml)

* Eclipse
  - Go to "Window" -> "Preferences", then to "Java" -> "Code Style".
  - In "Clean Up", click on "Import" and select the file [eclipse-java-magicdgs-cleanUp.xml](https://github.com/magicDGS/styleguide/blob/master/eclipse-java-magicdgs-cleanUp.xml)
  - In "Formatter", click on "Import" and select the file [eclipse-java-magicdgs-formatter.xml](https://github.com/magicDGS/styleguide/blob/master/eclipse-java-magicdgs-formatter.xml)
  - In "Organize Imports", click on "Import" and select the file [eclipse-java-magicdgs.importorder](https://github.com/magicDGS/styleguide/blob/master/eclipse-java-magicdgs.importorder)

## LICENSE

This files are licensed under the [CC-By 3.0 License](https://creativecommons.org/licenses/by/3.0/),
as the starting templates from the [Google styleguide repository](https://github.com/google/styleguide).

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>
