<h1 name="readme-top">ContentCleaner</h1>
<p align="center">
    <img src="https://img.shields.io/github/v/release/aljawaid/ContentCleaner?style=for-the-badge&color=brightgreen" alt="GitHub Latest Release (by date)" title="GitHub Latest Release (by date)">
    <img src="https://img.shields.io/github/downloads/aljawaid/ContentCleaner/total?style=for-the-badge&color=orange" alt="GitHub All Releases" title="GitHub All Downloads">
    <img src="https://img.shields.io/github/directory-file-count/aljawaid/ContentCleaner?style=for-the-badge&color=orange" alt="GitHub Repository File Count" title="GitHub Repository File Count">
    <img src="https://img.shields.io/github/repo-size/aljawaid/ContentCleaner?style=for-the-badge&color=orange" alt="GitHub Repository Size" title="GitHub Repository Size">
    <img src="https://img.shields.io/github/languages/code-size/aljawaid/ContentCleaner?style=for-the-badge&color=orange" alt="GitHub Code Size" title="GitHub Code Size">
</p>
<p align="center">
    <img src="https://img.shields.io/github/discussions/aljawaid/ContentCleaner?style=for-the-badge&color=blue" alt="GitHub Discussions" title="GitHub Discussions">
    <img src="https://img.shields.io/github/commits-since/aljawaid/ContentCleaner/latest?include_prereleases&style=for-the-badge&color=blue" alt="GitHub Commits Since Last Release" title="GitHub Commits Since Last Release">
    <img src="https://img.shields.io/github/commit-activity/m/aljawaid/ContentCleaner?style=for-the-badge&color=blue" alt="GitHub Commit Monthly Activity" title="GitHub Commit Monthly Activity">
    <a href="https://github.com/kanboard/kanboard" title="Kanboard - Kanban Project Management Software"><img src="https://img.shields.io/badge/Plugin%20for-kanboard-D40000?style=for-the-badge" alt="Kanboard"></a>
</p>

This tool allows admins to cleanup their Kanboard database by selectively deleting useless data saved by Kanboard and leftover data after uninstalling plugins. Keep your database clean and free from cluttered and expired data using cleaning jobs to solve specific application issues.

<p align="right">[<a href="#readme-bottom">&#8595; Bottom</a>] [<a href="#screenshots">&#8594; Next</a>] [<a href="#readme-top">&#8593; Top</a>]</p>

## Features

- Show a detailed database summary
  - Display extra tables which are created by plugins
  - Delete extra tables directly from the database
  - Easily identify plugin ownership of each extra table
- Show default database information
  - Highlight extra columns within tables and delete columns directly from the database
- Numbered cleaning jobs for easy reference
  - Each cleaning job is specific to a plugin or a default application setting
- Deep clean the database from all plugins and plugin related data
- **Automatic Cleaning Jobs:**
  - Purge Unused Plugin Registration Entries 
  - Clean All Unknown Tables and Columns 
- **Application Cleaning Jobs:**
  - Purge User Sessions
  - Restore Calendar Settings
  - Delete `Remember Me` Login Sessions
  - Delete Duplicate `Remember Me` Login Sessions
- **Plugin Cleaning Jobs:**
  - Remove [MetaMagik](https://github.com/creecros/MetaMagik "A Kanboard plugin") data
  - Remove [CostControl](https://github.com/aljawaid/CostControl "A Kanboard plugin") data
  - Remove [Bigboard](https://github.com/BlueTeck/kanboard_plugin_bigboard "A Kanboard plugin") data
  - Remove [Group_assign](https://github.com/creecros/Group_assign "A Kanboard plugin") data
  - Remove [SubtaskDueDate](https://github.com/eSkiSo/Subtaskdate "A Kanboard plugin") data
  - Remove [Wiki](https://github.com/funktechno/kanboard-plugin-wiki "A Kanboard plugin") data
  - Remove [TemplateManager](https://github.com/aljawaid/TemplateManager "A Kanboard plugin") data

<p align="right">[<a href="#readme-bottom">&#8595; Bottom</a>] [<a href="#features">&#8592; Previous</a>] [<a href="#usage">&#8594; Next</a>] [<a href="#readme-top">&#8593; Top</a>]</p>

## Screenshots

**Database Summary**  

![Summary](../master/Screenshots/screenshot-summary.png "Database Summary")

**Default Tables**  

![Summary](../master/Screenshots/screenshot-default-tables.png "Default Tables")

**Automatic Cleaning Jobs**  

![Summary](../master/Screenshots/screenshot-auto-cleaning-jobs.png "Automatic Cleaning Jobs")

<p align="right">[<a href="#readme-bottom">&#8595; Bottom</a>] [<a href="#features">&#8592; Previous</a>] [<a href="#installation--compatibility">&#8594; Next</a>] [<a href="#readme-top">&#8593; Top</a>]</p>

## Usage

Go to `Settings` &#10562; Content Cleaner

<p align="right">[<a href="#readme-bottom">&#8595; Bottom</a>] [<a href="#screenshots">&#8592; Previous</a>] [<a href="#authors--contributors">&#8594; Next</a>] [<a href="#readme-top">&#8593; Top</a>]</p>

## Installation & Compatibility

<details>
    <summary><strong>Installation</strong></summary>

- Install via the **[Kanboard](https://github.com/kanboard/kanboard "Kanboard - Kanban Project Management Software") Plugin Directory** or see [INSTALL.md](../master/INSTALL.md)
- Read the full [**Changelog**](../master/changelog.md "See changes") to see the latest updates

</details>
<details>
    <summary><strong>Compatibility</strong></summary>

- Requires [Kanboard](https://github.com/kanboard/kanboard "Kanboard - Kanban Project Management Software") ≥`1.2.20`
- **Other Plugins & Action Plugins**
  - _No known issues_
  - Compatible with [PluginManager](https://github.com/aljawaid/PluginManager)
- **Core Files & Templates**
  - _No template overrides_
  - _No database changes are made by this plugin other than the deletion of database content_
  - MS SQL databases are not supported

</details>
<details>
    <summary><strong>Translations</strong></summary>

- _Starter template available_

</details>

<p align="right">[<a href="#readme-bottom">&#8595; Bottom</a>] [<a href="#usage">&#8592; Previous</a>] [<a href="#license">&#8594; Next</a>] [<a href="#readme-top">&#8593; Top</a>]</p>

## Authors & Contributors

- [@aljawaid](https://github.com/aljawaid) - Author
- [Craig Crosby](https://github.com/creecros) - Contributor
- [Alfred Bühler](https://github.com/alfredbuehler) - Contributor
- _Contributors welcome_

<p align="right">[<a href="#readme-bottom">&#8595; Bottom</a>] [<a href="#installation--compatibility">&#8592; Previous</a>] [<a href="#readme-top">&#8593; Top</a>]</p>

## License

- This project is distributed under the [MIT License](../master/LICENSE "Read The MIT license")

<a name="readme-bottom"></a>
<p align="right">[<a href="#readme-top">&#8593; Top</a>]</p>
