# Third Party Dependencies

<!--[[[fill sbom_sha256()]]]-->
The [SBOM in CycloneDX v1.4 JSON format](https://git.sr.ht/~sthagen/persoonallisuus/blob/default/etc/sbom/cdx.json) with SHA256 checksum ([cb2bf119 ...](https://git.sr.ht/~sthagen/persoonallisuus/blob/default/etc/sbom/cdx.json.sha256 "sha256:cb2bf11936f97eb93df843b9dd4a81f05939623bc98da87143aab555b322a09a")).
<!--[[[end]]] (checksum: e8ec8d7eff934767cc414178ee3e290e)-->
## Licenses 

JSON files with complete license info of: [direct dependencies](direct-dependency-licenses.json) | [all dependencies](all-dependency-licenses.json)

### Direct Dependencies

<!--[[[fill direct_dependencies_table()]]]-->
| Name                                           | Version                                            | License     | Author                           | Description (from packaging data)                                                                        |
|:-----------------------------------------------|:---------------------------------------------------|:------------|:---------------------------------|:---------------------------------------------------------------------------------------------------------|
| [PyYAML](https://pyyaml.org/)                  | [6.0.1](https://pypi.org/project/PyYAML/6.0.1/)    | MIT License | Kirill Simonov                   | YAML parser and emitter for Python                                                                       |
| [lxml](https://lxml.de/)                       | [5.0.0](https://pypi.org/project/lxml/5.0.0/)      | BSD License | lxml dev team                    | Powerful and Pythonic XML processing library combining libxml2/libxslt with the ElementTree API.         |
| [msgspec](https://jcristharif.com/msgspec/)    | [0.18.5](https://pypi.org/project/msgspec/0.18.5/) | BSD License | Jim Crist-Harif                  | A fast serialization and validation library, with builtin support for JSON, MessagePack, YAML, and TOML. |
| [rtoml](https://github.com/samuelcolvin/rtoml) | [0.10.0](https://pypi.org/project/rtoml/0.10.0/)   | MIT License | Samuel Colvin <s@muelcolvin.com> | A better TOML library for python implemented in rust.                                                    |
<!--[[[end]]] (checksum: 8ab25968c8a1adee2489af821da7efef)-->

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
lxml==5.0.0
msgspec==0.18.5
PyYAML==6.0.1
rtoml==0.10.0
````
<!--[[[end]]] (checksum: 12ffb5dcc9a1c598aa365f62b1d55eb7)-->
