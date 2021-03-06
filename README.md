<h1 align="center">

<img src="https://raw.githubusercontent.com/Star-Athenaeum/Website/master/.github/git-readme.png?sanitize=true" width="300px" height="300px" alt="Logo" />
<br/>
UEESA WebAssembly App
</h1>
<div align="center">

[![Build](https://img.shields.io/github/workflow/status/Star-Athenaeum/UEESA-App/Build?style=flat-square)](https://github.com/Star-Athenaeum/UEESA-App/actions/workflows/dotnet-core.yml)
[![License: MIT](https://img.shields.io/github/license/Star-Athenaeum/Website?style=flat-square)](https://github.com/Star-Athenaeum/Website/blob/master/LICENSE)
[![Twitter](https://img.shields.io/twitter/url/http/shields.io.svg?style=flat-square&logo=twitter)](https://twitter.com/intent/tweet?hashtags=UEESA,StarCitizen&text=StarAthenaeum.+The+most+ambitious+tools+project+for+Star+Citizen&url=https://github.com/Star-Athenaeum)

</div>

Home to the cutting edge corner of the verse, where each and every citizen, pirate, syndicate leader and alike can learn a little more.

# Licensing

This project follows the [MIT License](https://github.com/Star-Athenaeum/Website/blob/master/LICENSE)

# Questions

Have a question? There is currently 1 way of doing this!
* Tweet [@Stryxus](https://twitter.com/Stryxus)

# Distribution

This website is distributed to [Azure](https://azure.microsoft.com/) with [Blaze](https://github.com/Star-Athenaeum/Blaze).

# Contributing

### Requirements
* Visual Studio 2019.
* ASP.NET Core
* .NET 5 SDK

Developing the website only requires you to run `Run_Blaze.cmd` at all times and leave it running in the background. This command file starts [Blaze](https://github.com/Star-Athenaeum/Blaze) which processes everything under wwwroot.
### IMPORTANT: Due to the current state of Blaze, you will need to change the path specified in `blaze-settings.json` (DO NOT COMMIT IT). If the `blaze-settings.json` changes, it is recommended to revert the file locally and pull the update then reapply your path.

To change the configuration of [Blaze](https://github.com/Star-Athenaeum/Blaze), you need to change `blaze-settings.json` in the Client project.

