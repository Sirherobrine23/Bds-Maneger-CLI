Maintenance Stops
===

After the new release of the [Bds Manger API](https://github.com/Bds-Maneger/bds_maneger_api) versions based on Shell Script are being maintained with less attention, if it is not updated for some years I strongly recommend using version based on NodeJS

# For a script in which you can do it manually.

This script appeared to simplify a way of managing Minecraft Bedrock Server, instead of writing and stopping the server, let everything be done by a script, Maintenance, management and backup. All in one place with just a few commands.

If you do not want to write several commands just use the bds-gui that is, a small extension for bds-cli, as usual open source for maintenance and contribution to the project. Link: https://github.com/Sirherobrine23/Bds-Maneger-GUI

# Command examples.

```
Bash# bds-config set Xbox=false port=19132 whitelist=true
Bash# CPU=true bds-status
Bash# bds-manger
```

* The `bds-manger` will show a diago box at the beginning in which you have chosen an option to continue.

* The `bds-status` is still under maintenance and modifications in `version 1.4.18` to make the use of the user better at the end better.

* For file management reasons, commands should always be used with sudo or with the root user. An alternative user form is being sought for everyone to use.

The `bds-common` package has only Minecraft Bedrock Server with directory modifications, the software belongs to Mojang Studio AB. Any term has to be accepted until I publish a form of agreement on installing the packages. Any image and name About Minecraft Content are from Mojang Studio AB, The `bds-manger` package is the property of Matheus Sampaio Queiroga, as maintenance and contribution of the content.
