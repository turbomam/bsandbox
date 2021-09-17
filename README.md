# bsandbox
a place to do bottom up exercises

see
- https://linkml.io/
- use template or https://linkml.io/linkml/generators/project-generator.html?highlight=template ?

- start with linkml individuals in json
- convert to yaml?

- try/practice
    - exception handling
    - make
    - various virtual environments
    - cookie cutter
    - tox
    - nlp
    - visualization
    - builing package and publishing
    - testing
    - GitHub actions
    - cli (click)
    - docstrings
    - ...

----

- clone this repo and cd into it
- `% python3 -m venv venv`
- `pip install -r requirements.txt`
    - try other virtual env and package installers
- `make all`

_Intel MacBook Pro 2020, macPS Big Sur 11.5.2_

many of these:
> DEPRECATION: Configuring installation scheme with distutils config files is deprecated and will no longer work in the near future. If you are using a Homebrew or Linuxbrew Python, please see discussion at https://github.com/Homebrew/homebrew-core/issues/76621
>>>>>>> d9b496c0ab2e069eefefb28222deda558c2b5429
    
> GEN: sqlddl
 SCHEMA: personinfo.yaml
 PARENT=personinfo/sqlschema
WARNING:SQLDDLGenerator:Unrecognized prefix: skos
 ARGS: {'mergeimports': False}
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
WARNING:root:UNKNOWN: XSDDate // <class 'linkml_runtime.utils.yamlutils.extended_str'>
ERROR:root:No PK for Address
  WRITING TO: personinfo/sqlschema/personinfo.sql


`% ./venv/bin/linkml-convert -m personinfo/personinfo.py -o person_glance_data.yaml -t yaml -C Person -s personinfo.yaml person_glance_data.json`
>WARNING:root:There is no established path to personinfo/personinfo.py - compile_python may or may not work
WARNING:JsonSchemaGenerator:Unrecognized prefix: skos
