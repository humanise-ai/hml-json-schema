# hml-json-schema
Humanise Markup Language (HML) json schema definition

This is a json schema definition for HML.

Authors of HML YAML files can install this in VS-Code in order to provide validation and auto-complete of HML code.

To install in VS-Code, follow these steps:
1. Go to the VS-Code Extensions palette, search for `red hat yaml` and install the YAML Language Support by Red Hat extension.
2. Go to Preferences -> Settings to open the settings page and search for yaml.
3. You should see a section entitled `[yaml]`. Press "Edit in settings.json".
5. Add the follow section, replacing any existing `yaml.schemas` section if it already exists:
```
  "yaml.schemas": {
    "https://raw.githubusercontent.com/humanise-ai/hml-json-schema/main/hml-json-schema.json": "*-hml.yaml"
  },
```
7. Save and restart VS-Code
8. Write your hml. Use ctrl-space to see options and watch auto-complete magic happen!
