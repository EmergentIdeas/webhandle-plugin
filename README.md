Webhandle Plugin Blank
======================

This project helps create a plugin for the webhandle web framework [https://github.com/EmergentIdeas/webhandle]. It
provides the directories and scripts needed to assemble a valid, usable plugin. By default, it will publish to a local
repo (not the ivy cache). From there, it's up to you to get it into your application.

This is not the easy way to start a webhandle application. For that checkout out the starter project on github
[https://github.com/EmergentIdeas/starter].

For You To Do
-------------

In build.xml, change:

>		change/me/to/your/project/package/name
>		change-me-to-organization-name
>		change-me-to-project-name
>		YOUR DESCRIPTION HERE

In ivy.xml, change:

>		change-me-to-organization-name
>		change-me-to-project-name

In settings.xml, change:

>		/data/repositories/ivyrepo/release

to a directory where plugin artifacts can be published.


To Use
------

Write code and templates, add templates and configure. To create the plugin artifacts, run:

ant dist

To publish to your local on disk repository, run:

ant pub