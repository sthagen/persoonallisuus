# Third Party Dependencies

<!--[[[fill sbom_sha256()]]]-->
The [SBOM in CycloneDX v1.4 JSON format](https://github.com/sthagen/pilli/blob/default/sbom.json) with SHA256 checksum ([c57a28f9 ...](https://raw.githubusercontent.com/sthagen/pilli/default/sbom.json.sha256 "sha256:c57a28f9c7493a7431e0f128d462784dbd4094c3822cc5a5bd460ba49bd80b98")).
<!--[[[end]]] (checksum: c4e49be2de2c0a38400e1185b532918b)-->
## Licenses 

JSON files with complete license info of: [direct dependencies](direct-dependency-licenses.json) | [all dependencies](all-dependency-licenses.json)

### Direct Dependencies

<!--[[[fill direct_dependencies_table()]]]-->
| Name                                                               | Version                                            | License     | Author                           | Description (from packaging data)                                                                |
|:-------------------------------------------------------------------|:---------------------------------------------------|:------------|:---------------------------------|:-------------------------------------------------------------------------------------------------|
| [PyYAML](https://pyyaml.org/)                                      | [6.0](https://pypi.org/project/PyYAML/6.0/)        | MIT License | Kirill Simonov                   | YAML parser and emitter for Python                                                               |
| [lxml](https://lxml.de/)                                           | [4.9.2](https://pypi.org/project/lxml/4.9.2/)      | BSD License | lxml dev team                    | Powerful and Pythonic XML processing library combining libxml2/libxslt with the ElementTree API. |
| [msgspec](https://jcristharif.com/msgspec/)                        | [0.11.0](https://pypi.org/project/msgspec/0.11.0/) | BSD License | UNKNOWN                          | A fast and friendly JSON/MessagePack library, with optional schema validation                    |
| [rtoml](https://github.com/samuelcolvin/rtoml/blob/main/README.md) | [0.9.0](https://pypi.org/project/rtoml/0.9.0/)     | MIT License | Samuel Colvin <s@muelcolvin.com> | A better TOML library for python implemented in rust.                                            |
<!--[[[end]]] (checksum: 1e49ed1cb24316a9e5722bfa3bc020ff)-->

### Indirect Dependencies

<!--[[[fill indirect_dependencies_table()]]]-->
| Name                                               | Version                                               | License     | Author            | Description (from packaging data)               |
|:---------------------------------------------------|:------------------------------------------------------|:------------|:------------------|:------------------------------------------------|
| [attrs](https://www.attrs.org/)                    | [22.2.0](https://pypi.org/project/attrs/22.2.0/)      | MIT License | Hynek Schlawack   | Classes Without Boilerplate                     |
| [click](https://palletsprojects.com/p/click/)      | [8.1.3](https://pypi.org/project/click/8.1.3/)        | BSD License | Armin Ronacher    | Composable command line interface toolkit       |
| [pyrsistent](https://github.com/tobgu/pyrsistent/) | [0.19.2](https://pypi.org/project/pyrsistent/0.19.2/) | MIT License | Tobias Gustafsson | Persistent/Functional/Immutable data structures |
<!--[[[end]]] (checksum: 22645116ee18efb7104020003d445c8c)-->

## Dependency Tree(s)

JSON file with the complete package dependency tree info of: [the full dependency tree](package-dependency-tree.json)

### Rendered SVG

Base graphviz file in dot format: [Trees of the direct dependencies](package-dependency-tree.dot.txt)

<img src="./package-dependency-tree.svg" alt="Trees of the direct dependencies" title="Trees of the direct dependencies"/>

### Console Representation

<!--[[[fill dependency_tree_console_text()]]]-->
````console
lxml==4.9.2
msgspec==0.11.0
PyYAML==6.0
rtoml==0.9.0
````
<!--[[[end]]] (checksum: 76235c9996d6027ee4575cad1dbc3e42)-->
