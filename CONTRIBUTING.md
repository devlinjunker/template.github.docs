# How to Contribute!

Thanks for helping out!

## Reporting Issues
The best way to [report an issue is through Github](../../issues). The owners of the repo should get an email notification whenever a new issue is created.


## Development 
This section details the steps to setup the project for development.

### Environment Setup and Tools
Cloning this repo requires the use of Git, or you can use the template feature provided by Github. You can also download an archive of the repository contents using the Github "Download" link and extract this to access all of the files and create a new Git repository with them.

Once you have a framework and development environment chosen for your project you should update your repo with specifics about how to install the tools and dependencies needed to run/debug/develop the application.

### Folder Structure
Break down how each folder is used in the repo and how different code file types should be organized.

```
- .github/
|-- ISSUE_TEMPLATE/  
|---- (Github Issue Template Files)
|-- workflows/
|---- (Github workflow .yaml files)
|-- (other github specific files)
- (project config files and READMEs)
```

### Scripts
Scripts are extremely useful for streamlining processes and typical developer actions, or verifying that standards are met. This section documents how they are  used in this project.

#### Github Workflows
[GitHub Workflows/Actions](https://docs.github.com/en/actions/configuring-and-managing-workflows/configuring-a-workflow) are added in `.github/workflows`. 
These are created with YAML files that define when the workflow should run and the steps it should take. 
Github can then enforce that these workflows are successful before Pull Requests are merged via the [Branch Settings Page](../../settings/branches).

**[Label Manager](./.github/workflows/manage-labels.yml)**  
This project defines the Github Labels in a [YAML file](./.github/labels.yaml) that is managed by the [Github Labeler Action](https://github.com/marketplace/actions/github-labeler). 
Any labels that are not defined in this file will be removed every time this action is run. **This does not affect PRs**


### Style Guide
Make sure to only include basic documentation and Github setup files in this Template!

