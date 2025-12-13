# PluginHub
 
A list of plugins that are used by [Pulsar](https://github.com/SpaceGT/Pulsar).

## Developers

Temporary [Plugin Developer's Guide](https://discord.com/channels/1378756728107040829/1446496490372726895) 
on the [Pulsar Discord](https://discord.gg/z8ZczP2YZY). It will be moved to a proper Wiki soon.

### TLDR

If you wish to make a plugin for Pulsar, there are a few steps:
1. Publish your code on GitHub, based on the [**Client Plugin Template**](https://github.com/viktor-ferenczi/se-client-plugin-template)
2. Fork this repository.
3. Add your XML plugin descriptor file to the `Plugins` folder in this repository.
   Example XML file: [SamplePlugin.xml](SamplePlugin.xml)
4. Submit a pull request. The approval team will approve or deny it.

For registering a client side mod use this example XML file [SamplePlugin.xml](SamplePlugin.xml),
then register it with a PR into `Plugins/Mods`. The same approval process applies.