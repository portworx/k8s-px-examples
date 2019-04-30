
# PORTWROX CHEATSHEET

In this cheatsheet, we are going to explore the basic operations available through the Portworx Command-Line Tool - `pxctl`

## 1.1 PXCTL Basics Commands

By default, the CLI displays the information in human readable form. For example, to learn more about the available commands, type pxctl help: `pxctl help` 
The current release of `pxctl` is located in the `/opt/pwx/bin/` directory of every worker node and requires that you run as it as a privileged user.

Find out the portwrox current version : `pxctl -v` or `pxctl --version` 

Check out the portwrox status : `pxctl status`

## 1.2 PXCTL Service Commands

Service operations  : `/opt/pwx/bin/pxctl service --help`
                    
```
NAME:
   pxctl service - Service mode utilities

USAGE:
   pxctl service command [command options] [arguments...]

COMMANDS:
     audit, a        Audit the PX node
     call-home       Enable or disable the call home feature
     diags, d        creates a new tgz package with minimal essential diagnostic information.
     drive           Storage drive maintenance
     email           Email setting commands
     exit, e         Stop the PX daemon
     info, i         Show PX module version information
     kvdb, k         PX Kvdb operations
     maintenance, m  Maintenance mode operations
     node-wipe, nw   Wipes PX configuration data on this node
     pool            Storage pool maintenance

OPTIONS:
   --help, -h  show help
```

## 1.3 Upgrade related operations 

##1.4 Log & Conf Files

##1.5 Events & Metrics

