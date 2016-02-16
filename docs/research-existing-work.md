# Notes on existing work

## CloudBees CD Workflow/Pipeline
Adds pipeline features such as execution, forking and parallel.
Jenkins specific.
Not a free plugin (?)

## Multi-Branch Project Plugin
I do not see that this could be used. The plugin seems too new (as they also
admit on the wiki).

## Jenkins Build Per Branch
The functionality and idea looks similar. But it is only for Jenkins and Git.
It also looks pretty dev oriented, for example requiring a Git clone of the
"build per branch" project repo.

## Jenkins Autojobs
Again specific to Jenkins, but supports multiple SCMs.
Does not use Job DSL.
Not sure if its API will meet our needs.

## Jenkins Job Builders
Looks like a good way to scale Job DSL.
Not sure if it makes sense to use for us.

## Jenkins Build Pipeline Plugin
It would be cool to have auto-created jobs linked together in a build pipeline
if the plugin is installed.