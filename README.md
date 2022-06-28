# POM as YAML

Thanks to [polyglot-maven](https://github.com/takari/polyglot-maven) project, we can write our Project Object Model (POM) in dialects other than XML.
This project is such an example and POM is written in YAML instead of XML.

In order enable a specific dialect, add `.mvn/extensions.xml` file to your project and add the corresponding dialect extension.