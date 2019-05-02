# ridi/actions
Github Actions for RIDI

* https://developer.github.com/actions/creating-github-actions/creating-a-docker-container/

## Actions

### apex

* http://apex.run/

```
action "Deploy" {
  uses = "ridi/actions/apex@master"
  args = "deploy --env production"
  secrets = ["AWS_ACCESS_KEY_ID", "AWS_SECRET_ACCESS_KEY"]
}
```
