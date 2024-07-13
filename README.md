# GPT-DB-Plugins
GPT-DB Plugins Repo, Which support AutoGPT plugin. 


## Installation
⚠️This is a work in progress⚠️

Here are the steps to configure GPT-DB Plugins:

1. Install GPT-DB
If you haven't done so, follow the installation instructions given by [GPT-DB](https://gpt-db.readthedocs.io/en/latest/getting_started/getting_started.html) to install it.

2. Download the plugins folder from the root of GPT-DB directory

In order to make it easier to use the plugin, we will load a dashboard drawing plugin by default when the task starts. 

To download it directly from your GPT-DB directory. 

3. Install Plugin dependencies
```
pip install -r requirements.txt
```
Each plugin will also have its own usage tutorial, you can find the specific usage method in the readme

## Plugins
> For interactionless use, set ALLOWLISTED_PLUGINS=example-plugin1,example-plugin2,example-plugin3 in your .env

There are two categories of plugins: built-in party and third party. built-in party plugins are included in this repo and are installed by default when the plugin platform is installed. Third-party plugins need to be added individually. Use built-in party plugins for widely-used plugins, and third-party for your specific needs. You can view all the plugins and their contributors on this directory.

You can also see the plugins here:

| Plugin       | Description     | Location |
|--------------|-----------|--------|
|  db_dashboard  | This gives GPT-DB info about data analysis.  | [dbgpt_plugins/db_dashboard](https://github.com/khulnasoft-lab/GPT-DB-Plugins/tree/main/src/dbgpt_plugins/db_dashboard)           |

## Configuration
For interactionless use, set:

ALLOWLISTED_PLUGINS=example-plugin1,example-plugin2,etc in your .env file to allow plugins to load without prompting. DENYLISTED_PLUGINS=example-plugin1,example-plugin2,etc in your .env file to block plugins from loading without prompting.


# Get Help
For more information, visit the [**Discord**](https://discord.gg/xfNDzZ9t) server.