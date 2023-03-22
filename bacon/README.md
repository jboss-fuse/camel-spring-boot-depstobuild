# Bacon config generator

The documentation here : 

https://project-ncl.github.io/bacon/guide/experimental.html

shows how to create a config that takes a BOM and creates PNC configs for the entries in that bom that need to be productized.

In order to use this feature, you need to add enableExperimental=true to your configuration profile - I added it to my ~/.config/pnc-bacon/config.yaml and that seemed to enable the experimental features.

bacon experimental dependency-generator generate camel-autobuilder.yaml > camel-results.yaml

generates the configs.
