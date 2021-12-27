# image-repo
Github + jsDelivr 图床

PicGo配置
```json
{
  "picBed": {
    "current": "github",
    "uploader": "github",
    "smms": {
      "token": ""
    },
    "list": [
      {
        "name": "SM.MS图床",
        "type": "smms",
        "visible": false
      },
      {
        "name": "腾讯云COS",
        "type": "tcyun",
        "visible": false
      },
      {
        "name": "GitHub图床",
        "type": "github",
        "visible": true
      },
      {
        "name": "七牛图床",
        "type": "qiniu",
        "visible": false
      },
      {
        "name": "Imgur图床",
        "type": "imgur",
        "visible": false
      },
      {
        "name": "阿里云OSS",
        "type": "aliyun",
        "visible": false
      },
      {
        "name": "又拍云图床",
        "type": "upyun",
        "visible": false
      }
    ],
    "github": {
      "branch": "master",
      "customUrl": "https://cdn.jsdelivr.net/gh/gcdd1993/image-repo@master",
      "path": "img/",
      "repo": "gcdd1993/image-repo",
      "token": ""
    }
  },
  "settings": {
    "shortKey": {
      "picgo:upload": {
        "enable": true,
        "key": "CommandOrControl+Shift+P",
        "name": "upload",
        "label": "快捷上传"
      }
    },
    "server": {
      "port": 36677,
      "host": "127.0.0.1",
      "enable": true
    },
    "privacyEnsure": true,
    "showUpdateTip": true,
    "autoStart": true,
    "rename": false,
    "autoRename": true
  },
  "picgoPlugins": {},
  "debug": true,
  "PICGO_ENV": "GUI",
  "needReload": false
}
```
