# sxalertd
This is a very hacky shell script that reads the D-Bus and draws notifications with [sxalert](https://github.com/MichaelDim02/sxalert).

## Run
sxalertd is meant to run as a daemon:
```
/path/to/sxalertd &
```
If you want to enable it for persistent use, add the above line to your `~/.xinitrc` file.
