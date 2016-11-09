# gitmylab

Ruby command line application for managing gitlab objects.

Developement still in progress !!!

TODO:
- Parameters validation
- tests, tests and tests
- documentation

## How to start - Configuration
To configure Gitmylab, all needed config Files are located in your Homedirectory inside the folder .gitmylab.
For Mac e.g.:
/Users/YourUser/.gitmylab/

* You need to specify the Git URL and set your personal Access Token, this will be done in the config file gitlab.yaml
* Inside the config file sync.yaml you have to add your local path, where all the modules have to be synced in.
* To configure a few other things, there are some other config files: access.yaml ad.yaml projects.yaml roles.yaml

But at least, with the two first steps above, you will be able to sync projects from a remote gitlab to your local machine

## Manage Gitlab Permissions
To manage Gitlab Permissions, use ```gitmylab access```

## Manage Gitlab Branches
To manage the branches in your Projects, use ```gitmylab branch```


## Manage Projects
To manage your Projects, use ```gitmylab project ```

### Sync your first Projects
To sync projects you can use the command

```gitmylab project sync ```

e.g. with the option -n you can define a namespace or with the option -a you can sync all projects from your gitlab server.

## Known Issues
* At the moment it's not possible to use gitmylab behind a Proxy.
