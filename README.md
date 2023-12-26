# Setting project with kedro on .gitpod.yml

Create your new repo run it on gitpod.

Copy .gitpod.yml file from this repo :) 

```
curl -s https://api.github.com/repos/AdamPrzychodniPrivate/starter/contents/.gitpod.yml | jq -r '.content' | base64 --decode > .gitpod.yml
```

commit and sync 

close your workspace 

and run it again :) 

Also there is a issue with notebook on gitpod you need run it with remote access to work in it, if you want but you can use diffrent ipnyb IDEs :)

kedro jupyter lab --ServerApp.allow_remote_access=True
