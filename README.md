# tue_documentation_python

This Sphinx configuration is fully dynamic configured for any catkin package with a python module. Add it as a submodule (or similar) to your package in the desired folder. Also add the following dependencies to your `package.xml` :

```xml
<doc_depend>python3-sphinx</doc_depend>
<doc_depend>python-sphinx-autoapi-pip</doc_depend>
<doc_depend>python-sphinx-rtd-theme-pip</doc_depend>
<doc_depend>python3-yaml</doc_depend>
```

**_Note_: This requires package format 2 or 3**
