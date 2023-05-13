# NodeGolangDockerTemplate

## フォルダ構成

```
- Template
  |- frontend : node
    |- Dockerfile : node:17.4.0-alpine
  |- backend : ruby
    |- Dockerfile : ruby:3.2.2
  |- database
    |- init : mysqlの初回起動時に呼ばれるスクリプト
    |- .env : mysqlのパスワードとか
    |- Dockerfile : mysql:8.0
  
```‣