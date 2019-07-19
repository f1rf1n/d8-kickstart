# d8-kickstart
All files en payout neccesary to quickly spin up a new D8 project (lando, git,composer etc)


Should work with phpStorm for xdebugging. Partly because of the php.ini which is loaded from .lando.yml in the project root.



Step guide:


- Lando init $projectname   ( D8, web )
- Clone this repo :
- edit .lando.yml  : change projectname (and any others settings)
-  edit local.settings.php to your liking. DB settings are the default lando d8 credentials
- set live site DBcredentials


