The Script SHACLTDTemplateGenerator.js takes a SHACL shape in jsonld format as input and gives a semantically enriched Thing Description template as output.

SHACLTDTemplateGenerator.js available from:
https://github.com/aparnasai/iotschema/tree/iotschema-TDGenerator/SHACL

How-to:
SHACL shapes should be stored in ./shapes directory
Resulting TD templates will be stored in ./GeneratedTDs directory

How to run the script?

>node SHACLTDTemplateGenerator.js <SHACL shape file in JSONLD>
>node SHACLTDTemplateGenerator.js LightShape-SmartThings.jsonld

