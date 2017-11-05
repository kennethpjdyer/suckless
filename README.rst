###################
Sucking Less
###################


This repository hosts my own builds and hacks of applications from `Suckless.org <https://suckless.org>`_.  

In the event that you're unfamiliar, Suckless applications are not intended for the uninitiate.  You need a good understanding of C to work with them and a better understanding to hack your own features into their code.  In all honesty, I have neither, but I see this as a good way to develop the skills.

Organization
=============

Each directory in this repository hosts an application downloaded from Suckless.  Within each directory, I have set up a series of sub-directories:

- ``base/`` Provides the base code downloaded from Suckless.
- ``current/`` Provides my current working implementation.
- ``%-devel/`` Reference implementations of new features currently in development.
- ``%-stable`` Reference implementations of new features that are ready for use.  You can use the ``.diff`` file to apply them to your repository.

The reason why I'm adding new features in this manner rather than through a branch is to keep the diffs relative small, allowing you to add a particular features rather than more bloated implementation that I'm using.

License
========

The base applications in this repository belong to Suckless.  You'll find a ``LICENSE`` file in each repository indicating ownership and their permitted uses.  They seem to favor the MIT/X Consortium License, which is fairly permissive from the start.

Current builds of each application may contain patches from other sources.  Some of which can be found on the Suckless website, some may derive from other sources.  I'll try to keep a log of what's in there in the event that you want to find something more advanced.

As always, my own code is available under the Revised BSD License.  Wherever possible I'll try to implement it a way that clearly delineates in comments or files what belongs to Suckless and what belongs to me.



