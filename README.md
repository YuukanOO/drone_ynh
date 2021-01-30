# Drone CI app for YunoHost

> _This package allows you to install Drone CI quickly and simply on a YunoHost server.  
> If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it._

**This is a work in progress to deploy Drone via Docker on Yunohost, upgrade script is not done yet so things may break!**

## Overview

Drone is a self-service Continuous Integration platform for busy development teams.

**Shipped version:** 1.10.1

## Screenshots

_TODO_

## Configuration

It only works with Gitea since this is the CVS I am using on Yunohost so you must have to follow the [instructions here](https://docs.drone.io/server/provider/gitea/) to generate client id and secret needed by this installation.

## Documentation

- Official documentation: https://docs.drone.io/

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported? Yes because it uses a Gitea server to authenticate
Can the app be used by multiple users? Yes, same reason as above

#### Supported architectures

- x86-64 - Tested only on this architecture but may work on other :/

## Limitations

- Any known limitations.

## Links

- Report a bug: https://github.com/YuukanOO/drone_ynh/issues
- App website: https://www.drone.io/
- Upstream app repository: https://github.com/drone/drone
- YunoHost website: https://yunohost.org/
