# Starter for a Drupal 8 Composer base project

1. Fork this project or otherwise set it as the "upstream" codebase

2. Change the `name:` variable in the `composer.json` file to `MY_NAMESPACE/MY_PROJECT_NAME`

3. Change `description:` and `authors:` variables as needed in the `composer.json` file

4. Optionally, create dependency for "D8 profile starter."

```
composer require jeff-cardwell/d8_profile_starter
```

5. Following initial install base configuration, add config files to `config/install` folder.  For future installs, select "config_installer" as the install profile.