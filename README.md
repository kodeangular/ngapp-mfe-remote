# STEPS

- https://github.com/angular-architects/module-federation-plugin/blob/main/libs/mf/tutorial/tutorial.md

- ng new hostapp --create-application="false"
- ng generate application host
- ng add @angular-architects/module-federation --project host --type host --port 4200

- ng new mfe1 --create-application="false"
- ng generate application mfe1
- ng add @angular-architects/module-federation --project mfe1 --type remote --port 4201

# ngapp-mfe-remote

COST-BASIS-UI : REMOTE-MODULE

- NG-MODULE
  - DOD
  - MASK

NEXT360 : SHELL
