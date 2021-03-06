# jiraissues

Builds on CircleCI: 
[![CircleCI](https://circleci.com/gh/lxklssn/jiraissues/tree/master.svg?style=svg)](https://circleci.com/gh/lxklssn/jiraissues/tree/master)

## Usage

Include this plugin in your project. Visit this 
[plugin's page on plugins.gradle.org](https://plugins.gradle.org/plugin/de.lxklssn.jiraissues) 
for more information. 

```
plugins {
  id "de.lxklssn.jiraissues" version "1.0.3"
}
```

## Contributing

Feel free to open issues for new ideas or bugs and submit pull requests if you want to add some features.

### Repository structure

This repository contains the plugin and a sandbox project for manual tests when editing the plugin.

#### ./jiraissues-plugin-sandbox

This is a project which uses the plugin. The plugin is included in this build in order to test changes without the need to deploy the plugin first.
Run your manual tests here. You can change the sandbox project to demonstrate new features.

```
> cd jiraissues-plugin-sandbox
> gradlew getIssues
```