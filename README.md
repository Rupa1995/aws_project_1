## sam app setup

- install aws cli
- install aws sam cli
- aws --version
- sam --version
- sam init
- cd sam_project //here will be sam_template.toml file which will be used by sam build
- sam build
```
=========================
Commands you can use next
=========================
[*] Validate SAM template: sam validate
[*] Invoke Function: sam local invoke
[*] Test Function in the Cloud: sam sync --stack-name {{stack-name}} --watch
[*] Deploy: sam deploy --guided
```
- sam validate
- sam local start-lambda
- sam local invoke HelloWorldFunction --event ./events/event.json (in new terminal)
- sam deploy --guided // guided option will guide through the deployment steps
