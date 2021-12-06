# hml-json-schema
Humanise Markup Language (HML) json schema definition

This is a json schema definition for HML.

Authors of HML YAML files can install this in VS-Code in order to provide validation and auto-complete of HML code.

To install in VS-Code, follow these steps:
1. Go to File -> Preferences -> Settings (or use the Command Pallete) to open the settings page and search for yaml.
2. Open the settings for the YAML extension and search for "Yaml: Schemas" and click "Edit in settings.json".
3. The "settings.json" file will open. you need to search again for the "yaml.schemas" object. If it doesn´t exist yet, you will have to create it.
4. This property represents a key-value, where the key is the absolute path to the schema file on your system and the value is a glob expression that specifies the files that the schema will be applied. e.g. you can set it to `"*-hml.yaml"` to ensure all files ending `-hml.yaml` will have the schema applied to them.
5. Restart vs-code
6. Write your hml. Use ctrl-space to see options and watch auto-complete magic happen!
