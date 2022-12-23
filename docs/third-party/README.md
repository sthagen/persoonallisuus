# Third Party Dependencies

<!--[[[fill sbom_sha256()]]]-->
The [SBOM in CycloneDX v1.4 JSON format](https://github.com/sthagen/pilli/blob/default/sbom.json) with SHA256 checksum ([d708fca7 ...](https://raw.githubusercontent.com/sthagen/pilli/default/sbom.json.sha256 "sha256:d708fca745d502f3beb3ea9bb2238e6bb903a78cf79328555846df1f62751dcb")).
<!--[[[end]]] (checksum: 17d6c6e16e5a766e476ff4e8925dd431)-->
## Licenses 

JSON files with complete license info of: [direct dependencies](direct-dependency-licenses.json) | [all dependencies](all-dependency-licenses.json)

### Direct Dependencies

<!--[[[fill direct_dependencies_table()]]]-->
| Name                                                               | Version                                            | License     | Author                           | Description (from packaging data)                                                                |
|:-------------------------------------------------------------------|:---------------------------------------------------|:------------|:---------------------------------|:-------------------------------------------------------------------------------------------------|
| [PyYAML](https://pyyaml.org/)                                      | [6.0](https://pypi.org/project/PyYAML/6.0/)        | MIT License | Kirill Simonov                   | YAML parser and emitter for Python                                                               |
| [lxml](https://lxml.de/)                                           | [4.9.2](https://pypi.org/project/lxml/4.9.2/)      | BSD License | lxml dev team                    | Powerful and Pythonic XML processing library combining libxml2/libxslt with the ElementTree API. |
| [msgspec](https://jcristharif.com/msgspec/)                        | [0.11.0](https://pypi.org/project/msgspec/0.11.0/) | BSD License | Jim Crist-Harif                  | A fast and friendly JSON/MessagePack library, with optional schema validation                    |
| [rtoml](https://github.com/samuelcolvin/rtoml/blob/main/README.md) | [0.9.0](https://pypi.org/project/rtoml/0.9.0/)     | MIT License | Samuel Colvin <s@muelcolvin.com> | UNKNOWN                                                                                          |
<!--[[[end]]] (checksum: 8b3c9ce1d2d2edf0fab2f8e8c223617b)-->

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
