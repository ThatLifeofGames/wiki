---
title: Templates
description: Xenon gives you access to hundreds of free templates. In contrast to backups, templates are public and can be used by everyone.
published: true
date: 2020-09-01T06:59:04.152Z
tags: xenon, support
editor: markdown
---

# List of templates
You can find a list of templates at [templates.xenon.bot](https://templates.xenon.bot). Most of them can be loaded using Xenon or the discord template feature. Some legace templates are considered internal and can only be loaded using Xenon.

<br />

# Loading a template

Loading a template replaces all channels and roles in the discord. It does not kick the members.

You can also load any discord template in an **existing** server by supplying the template link, or supply the name to load one of Xenon's old templates.

## Syntax

`x!template load <template name/template URL> [options...]`

## Arguments

# Tabs {.tabset}
## template name/link

The name or link of the template you want to load

`required`

## options

A list of arguments, separated by a space. Putting a `!` in front of the argument disables the option.

`*` enables all
`!*` disables all

**Valid Arguments**: `channels delete-channels roles delete-roles`

**Example**: `x!backup load <backup-id> !* delete-roles roles` will only load roles
**Example**: `x!backup load <backup-id> !delete-roles !channels` will load everything beside channels

<br />

# Creating a template

Create template of your server and put it on Xenon's [template list](https://templates.xenon.bot).

Head over to the server you want to create a template of, go to your server settings and look for the "Server Template" tab. Fill out all the required details. 

![createtemplate.png](/createtemplate.png)

> Quick reminder that all templates are public! Do not share share private information in templates.
{.is-danger}

## Adding to Xenon's template list

Click copy on the template link, and head over to [here](https://templates.xenon.bot/templates/add) and paste your template link in.

It should now be avaliable on the Xenon templates site.



