Style Guides for magicDGS projects
==================================

This repository contains style guides for code in my projects, to facilitate 
formatting with different IDEs for contributors and maintain consistency in
my code.

They are based in the [Google Style Guides](https://google.github.io/styleguide/javaguide.html)
for Java, with the following changes:

* Blocks of non-static imports ordering:
  1. `org.magicdgs.*`
  2. other packages in alphabetical order
  3. `java.*` and `javax.*`
* Indentation:
  - +4 spaces for new blocks
  - Double for continuation blocks
  - No alignment in multi-line statements
* Line-wrapping:
  - Enum constants are always wrapped
  - Annotations are always wrapped, but not the parameters even if they exceed the line limit
* Javadoc:
  - At-clauses descriptions are aligned
  - Blank lines after description, @param and @return

## SETTING UP IDE

* IntelliJ
  - Go to "Preferences" and them to "Coding Style" in IntelliJ.
  - Inport [intellij-java-magicdgs-style.xml](https://github.com/magicDGS/styleguide/intellij-java-magicdgs-style.xml)

## LICENSE

This files are licensed under the [CC-By 3.0 License](https://creativecommons.org/licenses/by/3.0/),
as the starting templates from the [Google styleguide repository](https://github.com/google/styleguide).

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>