Un outil pour ouvrir ton Yunohost à l'Internet, en passant par une machine à distance sur le cloud

L'un des défis classiques de l'auto-hébergement consiste à rendre tes services (par exemple, ton blog personnel)
accessibles à tout le monde sur l'Internet ouvert. Certains fournisseurs d’accès Internet t'attribuent une adresse IP
dédiée et te permettent de configurer ta box pour rediriger les ports nécessaires si tu le souhaites.

Cependant, pour une multitude d’autres raisons, cette solution classique peut ne pas être possible à toi. Par exemple,
peut-être que tu n'as pas la main sur la box Internet, ou tu préféres ne pas la modifier, ou encore tu héberges tes
services sur un Raspberry Pi connecté via le partage de connexion de ton téléphone, etc.

## Mode d’emploi

Premièrement, tu dois installer jauto-expose sur une machine dans le cloud, comme décrit par les
instructions [sur la page du projet](https://git.sitegui.dev/sitegui/jauto-expose/src/branch/main/README_fr.md).

Puis, installe cette application avec l'adresse IP et le token secret obtenus dans l'étape précédente.

