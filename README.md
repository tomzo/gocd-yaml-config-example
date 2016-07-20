# gocd-yaml-config-example
GoCD example configuration in YAML

Install [GoCD YAML configuration plugin](https://github.com/tomzo/gocd-yaml-config-plugin) and add this to your XML config:
```xml
<config-repos>
  <config-repo plugin="yaml.config.plugin">
    <git url="https://github.com/tomzo/gocd-yaml-config-example.git" />
  </config-repo>
</config-repos>
```
