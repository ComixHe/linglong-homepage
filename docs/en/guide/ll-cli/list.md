# List Installed Apps

Use `ll-cli list` to view the installed Linglong apps.

View the help information of `ll-cli list` command.

```bash
ll-cli list --help
```

Here is the outputs：

```text
Usage: ll-cli [options] list

Options:
  -h, --help                           Displays help on commandline options.
  --help-all                           Displays help including Qt specific
                                       options.
  --type <--type=installed>            query installed app
  --repo-point <--repo-point=flatpak>  app repo type to use
  --nodbus                             execute cmd directly, not via dbus

Arguments:
  list                                 show installed application
```

To view the installed `runtime` and apps, run `ll-cli list`:

```bash
ll-cli list
```

Here is the outputs:

```text
appId                           name                            version         arch        channel         module      description
org.deepin.Runtime              runtime                         20.5.0          x86_64      linglong        runtime     runtime of deepin
org.deepin.calculator           deepin-calculator               5.7.21.4        x86_64      linglong        runtime     calculator for deepin os
org.deepin.camera               deepin-camera                   6.0.2.6         x86_64      linglong        runtime     camera for deepin os
```
