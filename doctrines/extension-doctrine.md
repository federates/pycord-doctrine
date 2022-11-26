# Extension Doctrine

This doctrine is made both to make extension development for Pycord more standardized and easier for users.

## New Extensions

New extensions cannot be named the same as pycord-provided extensions. And new extensions have to be named like an extension.
The import location and pypi project if so should start with pycord.ext.

## Extension Functionality

While Pycord in some cases specializes extensions, like state having access to and storing intents, foreign or outsider extensions shall not modify or change any part of **existing** Pycord classes, methods, functions, and attributes.
They may however subclass or remake said functions and an exclusion is giving for extensions which provide cogs and override on_attach.

## Extension Integration Policy

Extensions in some cases may be accepted into Pycord to be integrated into its own codebase. In such cases the owner agrees to forfeit their previous copyright on the extension and replace it with Pycord's own. The owner could also agree to a dual-license agreement where they stay on the license for that extension (only for old files, new files shall only be single-licensed to Pycord).
An extension cannot be accepted if it does not use the MIT license, or a license compatible with it.

Extensions may only be accepted if they don't require any extra requirements, have messy code, or are otherwise useless or unused.
