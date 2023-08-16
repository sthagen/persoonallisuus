# Third Party Dependencies

<!--[[[fill sbom_sha256()]]]-->
The [SBOM in CycloneDX v1.4 JSON format](https://git.sr.ht/~sthagen/persoonallisuus/blob/default/sbom/cdx.json) with SHA256 checksum ([dfae6ae3 ...](https://git.sr.ht/~sthagen/persoonallisuus/blob/default/sbom/cdx.json.sha256 "sha256:dfae6ae30796f98935c7d828f9bbfce603cb80e68d515477fd0302a6b254f4c6")).
<!--[[[end]]] (checksum: 9cb3d54a36023d687e56cb893d9d6000)-->
## Licenses 

JSON files with complete license info of: [direct dependencies](direct-dependency-licenses.json) | [all dependencies](all-dependency-licenses.json)

### Direct Dependencies

<!--[[[fill direct_dependencies_table()]]]-->
| Name                                           | Version                                            | License     | Author                           | Description (from packaging data)                                                                        |
|:-----------------------------------------------|:---------------------------------------------------|:------------|:---------------------------------|:---------------------------------------------------------------------------------------------------------|
| [PyYAML](https://pyyaml.org/)                  | [6.0.1](https://pypi.org/project/PyYAML/6.0.1/)    | MIT License | Kirill Simonov                   | YAML parser and emitter for Python                                                                       |
| [lxml](https://lxml.de/)                       | [4.9.3](https://pypi.org/project/lxml/4.9.3/)      | BSD License | lxml dev team                    | Powerful and Pythonic XML processing library combining libxml2/libxslt with the ElementTree API.         |
| [msgspec](https://jcristharif.com/msgspec/)    | [0.18.1](https://pypi.org/project/msgspec/0.18.1/) | BSD License | Jim Crist-Harif                  | A fast serialization and validation library, with builtin support for JSON, MessagePack, YAML, and TOML. |
| [rtoml](https://github.com/samuelcolvin/rtoml) | [0.9.0](https://pypi.org/project/rtoml/0.9.0/)     | MIT License | Samuel Colvin <s@muelcolvin.com> | A better TOML library for python implemented in rust.                                                    |
<!--[[[end]]] (checksum: 4b480cc500af155a97b8b93458fe1ba4)-->

### Indirect Dependencies

<!--[[[fill indirect_dependencies_table()]]]-->
| Name | Version | License | Author | Description (from packaging data) |
|:-----|:--------|:--------|:-------|:----------------------------------|
<!--[[[end]]] (checksum: 8a87b89207db0be2864af66f9266660c)-->

## Dependency Tree(s)

JSON file with the complete package dependency tree info of: [the full dependency tree](package-dependency-tree.json)

### Rendered SVG

Base graphviz file in dot format: [Trees of the direct dependencies](package-dependency-tree.dot.txt)

<img src="./package-dependency-tree.svg" alt="Trees of the direct dependencies" title="Trees of the direct dependencies"/>

### Console Representation

<!--[[[fill dependency_tree_console_text()]]]-->
````console
lxml==4.9.3
msgspec==0.18.1
PyYAML==6.0.1
rtoml==0.9.0
````
<!--[[[end]]] (checksum: 509fac431274ae37c2c84921ed6ecf91)-->
