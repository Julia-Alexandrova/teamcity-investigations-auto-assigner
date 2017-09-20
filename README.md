[![JetBrains team project](http://jb.gg/badges/team.svg)](https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


# TeamCity Investigations Auto-Assigner

## General Info
* Vendor: JetBrains
* License: [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
* Plugin type: free, open-source

## Plugin Description
Assigns investigations automatically when it is clear who is responsible for the failure.

So far uses two heuristics:

* If user is the only committer to the build, he/she is responsible.
* If user is the only one who changed the files, whose names appear in test or build problem error text, he/she is responsible.

## Status
Working prototype is implemented.

## Known Issues
Has no settings yet, so cannot be disabled for some projects.

## Download
http://teamcity.jetbrains.com/viewLog.html?buildId=lastSuccessful&buildTypeId=TeamCityPluginsByJetBrains_InvestigationsAutoAssigner_BuildAgainstTeamCity81x&tab=artifacts

## TeamCity Versions Compatibility
Compatible with TeamCity 8.1.2 and later.

## Installation
Copy the plugin zip into the <[TeamCity Data Directory](http://confluence.jetbrains.com/display/TCD8/TeamCity+Data+Directory)>/plugins directory ([more on this](http://confluence.jetbrains.com/display/TCD8/Installing+Additional+Plugins#InstallingAdditionalPlugins-InstallingTeamCityplugins)).

## Feedback
Everybody is encouraged to try the plugin and provide feedback in the [forum](http://devnet.jetbrains.net/community/teamcity/teamcity) or post bugs into the [issue tracker](http://youtrack.jetbrains.net/issues/TW).
Please make sure to note the plugin version that you use.
