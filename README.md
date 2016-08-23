# meshblu-show

# how to test

Show meshblu_show.html in your blowser with the following parameters.

http:///xxxx.com/meshblu_show.html?myuuid=xxx&mytoken=xxx&suuid=xxx&server=xxx&port=xxx

Type the following command in your terminal.

curl -X POST "http://xxx/messages" -H "Content-Type: application/json" -d '{"devices": "xxx", "payload": {"command":"<h1>hello</h1>"}}' --header "meshblu_auth_uuid:xxx" --header "meshblu_auth_token: xxx"
