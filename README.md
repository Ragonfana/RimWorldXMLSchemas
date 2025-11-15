# RimWorld XML Schema files

_Please review the [LICENSE](/LICENSE) before contributing to this project. By making any contribution to this project, you agree to the terms of the LICENSE._

This is a collection of implied XML schema files in .xsd format for RimWorld mod development, inspired by the work of [Sam Hunt](https://github.com/sam-hunt/RimworldXsd). At time of writing, these files' rules were referenced primarily via the [information publicly available on the RimWorld wiki](https://rimworldwiki.com/wiki/Modding_Tutorials).

This project only contains metadata files for RimWorld mods for now. If you're interested in rudimentary .xsd for RimWorld's Defs, check out my bugfix-fork of [RimWorld XSD Schema Generator](https://github.com/Ragonfana/RimworldXsd)

XML schema is restrictive, and I am new to it as well, so this may not be the best structure. For example, the functionality of ModMetaData at time of writing forces the About.xml to be in a certain order to accommodate the `<author>` field, but this is not a canonical feature of RimWorld's XML parser (order-agnostic). While I did use this forced ordering to make the About.xml more human-readable, I'm not sure if it's appropriate given the purpose of an inferred XML schema. This project is open to PRs/issues to discuss these kinds of issues!

W3schools has an [excellent guide and reference on XML Schema Language](https://www.w3schools.com/xml/schema_intro.asp).

# TODO

Documentation

Portions of the materials used to create this content/mod are trademarks and/or copyrighted works of Ludeon Studios Inc. All rights reserved by Ludeon. This content/mod is not official and is not endorsed by Ludeon.
