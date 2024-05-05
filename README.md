# autopcr

[![License](https://img.shields.io/github/license/cc004/autopcr)](LICENSE)

自动清日常
bug反馈/意见/交流群: 885228564

请先运行一次`download_web.py`下载前端资源。

## HTTP 服务器模式

```bash
py -3.8 httpserver_test.py
```

访问`/daily/login`

## Hoshino插件模式

使用前请更新Hoshino到最新版，并**更新Hoshino的配置文件`__bot__.py`**

## Credits
- aiorequests 来自 [HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot)
- 图片绘制改自 [convert2img](https://github.com/SonderXiaoming/convert2img)
- 前端html来自 [AutoPCR_Web](https://github.com/Lanly109/AutoPCR_Web)
- ~~前端html来自 [autopcr_web](https://github.com/cca2878/autopcr_web)~~
- ~~前端html来自 [AutoPCR_Archived](https://github.com/watermellye/AutoPCR_Archived)~~
- ~~模型生成来自 [PcrotoGen](https://github.com/cc004/PcrotoGen)~~

## add
项目克隆自cc004的autopcr

仅仅增加了查询竞技场前排用户名称账号id功能，查询request需要消耗时间，查询速度优化todo

可自行修改增加autopcr/module/modules下init文件和tools文件（粘贴本仓库新增代码），或者git clone 该jjclist分支
可切换至仅查ID和排名，不查用户名提高查询速度，自行在tools.py中注释对应代码即可（但是没有用户名我怎么知道是谁，或许可以加个头像信息展示（doge ）

