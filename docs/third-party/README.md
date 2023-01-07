# Third Party Dependencies

<!--[[[fill sbom_sha256()]]]-->
The [SBOM in CycloneDX v1.4 JSON format](https://git.sr.ht/~sthagen/persoonallisuus/blob/default/sbom.json) with SHA256 checksum ([94584db9 ...](https://git.sr.ht/~sthagen/persoonallisuus/blob/default/sbom.json.sha256 "sha256:94584db9b7aac7d9c719ac66404cd8e4c55550ae3583f9d56daeabb2da2d47ef")).
<!--[[[end]]] (checksum: 1617bfce0997f27829b0a9711223b84d)-->
## Licenses 

JSON files with complete license info of: [direct dependencies](direct-dependency-licenses.json) | [all dependencies](all-dependency-licenses.json)

### Direct Dependencies

<!--[[[fill direct_dependencies_table()]]]-->
| Name                                                               | Version                                            | License     | Author                           | Description (from packaging data)                                                                |
|:-------------------------------------------------------------------|:---------------------------------------------------|:------------|:---------------------------------|:-------------------------------------------------------------------------------------------------|
| [PyYAML](https://pyyaml.org/)                                      | [6.0](https://pypi.org/project/PyYAML/6.0/)        | MIT License | Kirill Simonov                   | YAML parser and emitter for Python                                                               |
| [lxml](https://lxml.de/)                                           | [4.9.2](https://pypi.org/project/lxml/4.9.2/)      | BSD License | lxml dev team                    | Powerful and Pythonic XML processing library combining libxml2/libxslt with the ElementTree API. |
| [msgspec](https://jcristharif.com/msgspec/)                        | [0.12.0](https://pypi.org/project/msgspec/0.12.0/) | BSD License | Jim Crist-Harif                  | A fast and friendly JSON/MessagePack library, with optional schema validation                    |
| [rtoml](https://github.com/samuelcolvin/rtoml/blob/main/README.md) | [0.9.0](https://pypi.org/project/rtoml/0.9.0/)     | MIT License | Samuel Colvin <s@muelcolvin.com> | A better TOML library for python implemented in rust.                                            |
<!--[[[end]]] (checksum: ca5f745ce3d3243635cede2e0dae66ed)-->

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
lxml==4.9.2
msgspec==0.12.0
PyYAML==6.0
rtoml==0.9.0
````
<!--[[[end]]] (checksum: 3722b6d04b62374dde7655f6eb5c9896)-->
