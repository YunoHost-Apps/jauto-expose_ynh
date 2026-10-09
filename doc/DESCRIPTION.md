A tool for opening your YunoHost to the Internet, using a remote cloud machine as a passage.

A typical challenge when self-hosting is how to make your services (say, your personal blog) accessible to anyone on the open Internet. Some Internet providers give you a dedicated IP and allow you to configure your router to redirect the necessary ports if you feel like doing it.

However, for a multitude of other reasons, that typical solution may not be available for you. Say, maybe you don't have access to the router, or you prefer not changing it, or you're hosting in a Raspberry Pi tethering from your phone, etc.

## How to use

First, you need to install jauto-expose on a machine in the cloud. Follow the instructions [on the project's page](https://git.sitegui.dev/sitegui/jauto-expose/src/branch/main/README.md).

Then, install this app with the IP and token provided obtained in the step above.
