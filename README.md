## Ground Control

Ground Control is a simple SSH wrapper that was born out of necessity.
The script was created for personal use, so use it at your own risk.

## Features

The purpose of this wrapper is to autoselect the connection string
required for an SSH connection as well as the correct keys and ports
based on a settings file. It dynamically changes those by verifying
the what the current IP address is and comparing it to the settings.


## Sameple Settings file:

This information comes from your usual SSH connecton string.

**Example: ssh foobar@foo.bar.com -p 22**

The file would look something like this.

username=foobar
hostname=foo.bar.com

local=22
remote=60022

key=

office=226.233.236.128
