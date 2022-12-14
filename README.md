# leptweb

## Develop Environment Configuration

```bash
npx create-react-app my-app
cd my-app
## for easyui
npm install rc-easyui --save
npm run start
```

### Json server

```bash
mkdir __json_server__mock__
touch __json_server_mock__/db.json
npm i json_server
# in package.json add scripts
# {
# "json-server": "json-server __json_server_mock__/db.json --watch --port 3001"
# }
npm run json-server
```

### qs
```bash
npm i qs
# usage
# qs.stringify
```
