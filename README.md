<p align="center">
  scoop-apps
</p>
<p align="center">
  <a href="https://github.com/star2000/scoop-apps"><img alt="GitHub" src="https://img.shields.io/badge/Readme--Style-standard--repository-brightgreen?style=flat-square&color=f83500"/></a>
  <a href="https://github.com/star2000/scoop-apps"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/star2000/scoop-apps?style=flat-square"/></a>
  <a href="https://github.com/kkzzhizhou"><img alt="GitHub user" src="https://img.shields.io/badge/author-kkzzhizhou-brightgreen?style=flat-square"/></a>
</p>

## 介绍

此仓库每天自动合并其他 scoop 仓库的更新

注意：如果仓库描述文件过时或者安装等问题，请根据仓库根路径的 app-contributor-list.csv 到相应的仓库提交 issues

## 特性

- 每天更新
- 仓库列表根据项目[scoop-directory](https://github.com/rasa/scoop-directory)动态生成
- 自动处理同名文件，并优先采用较新版本, 重名文件以"软件-贡献人 ID"重命名
- 自动去重（基于 md5)
- json 格式检验
- 支持仓库推荐、不推荐列表

## 说明

- 可接受仓库推荐，提交 pr 至 bucket-recommend.txt 即可
- 可接受"不维护仓库清理”，需在 pr 中说明理由，提交 pr 至 bucket-not-recommend.txt 即可
- **未对仓库软件来源进行安全检验，请自行甄别恶意软件，或者使用杀毒软件**
- 如果有软件安装问题，请参考仓库根路径的 app-contributor-list.csv 到相应的仓库提交 issues

## 使用方法

```
scoop bucket add apps https://github.com/star2000/scoop-apps
```

### 安装部分软件 Hash Check Failed

因描述文件更新有概率更新到错误的文件，所以安装时出现“Hash Check Failed”，可以使用`-s`忽略，比如`scoop install xxx -s`即可，不放心的话可以到官网校验，或者根据仓库根路径的 app-contributor-list.csv 到相应的仓库提交 issues

## 感谢

- [scoop-directory](https://github.com/rasa/scoop-directory)

## 合并仓库列表

- kkzzhizhou/scoop-zapps
- HCLonely/my-scoop-bucket
- Weidows-projects/scoop-3rd
- SayCV/scoop-cvp
- ScoopInstaller/PHP
- sliots/ScoopBucket
- ScoopInstaller/Extras
- chawyehsu/dorado
- matthewjberger/scoop-nerd-fonts
- Calinou/scoop-games
- ivaquero/scoopet
- ScoopInstaller/Java
- ScoopInstaller/Versions
- TheRandomLabs/Scoop-Spotify
- borger/scoop-galaxy-integrations
- TheCjw/scoop-retools
- kodybrown/scoop-nirsoft
- TheRandomLabs/scoop-nonportable
- littleli/scoop-clojure
- ScoopInstaller/Nirsoft
- scoopcn/scoopcn
- kkzzhizhou/scoop-zapps
- rasa/scoops
- kidonng/sushi
- ScoopInstaller/Nonportable
- Paxxs/Cluttered-bucket
- KNOXDEV/wsl
- ACooper81/scoop-apps
- echoiron/echo-scoop
- cderv/r-bucket
- hermanjustnu/scoop-emulators
- couleur-tweak-tips/utils
- dodorz/scoop
- borger/scoop-emulators
- ViCrack/scoop-bucket
- everyx/scoop-bucket
- niheaven/scoop-sysinternals
- whoopscs/scoop-security
- Qv2ray/mochi
- wangzq/scoop-bucket
- kiennq/scoop-misc
- TheRandomLabs/Scoop-Bucket
- akirco/aki-apps
- wzv5/ScoopBucket
- zhoujin7/tomato
- TheRandomLabs/Scoop-Python
- DoveBoy/Apps
- jonz94/scoop-sarasa-nerd-fonts
- charmbracelet/scoop-bucket
- amorphobia/siku
- naderi/scoop-bucket
- hu3rror/scoop-muggle
- NyaMisty/scoop_bucket_misty
- noql-net/scoop
- ygguorun/scoop-bucket
- aliesbelik/poldi
- cmontage/scoopbucket-third
- Velgus/Scoop-Portapps
- iquiw/scoop-bucket
- liaoya/scoop-bucket
- AStupidBear/scoop-bear
- batkiz/backit
- ChungZH/peach
- 42wim/scoop-bucket
- brian6932/dank-scoop
- abgox/abgo_bucket
- jfut/scoop-jfut
- kengwang/scoop-ctftools-bucket
- SayCV/scoop-cvp
- cc713/ownscoop
- starise/Scoop-Confetti
- aoisummer/scoop-bucket
- starise/Scoop-Gaming
- seumsc/scoop-seu
- Weidows-projects/scoop-3rd
- Darkatse/Scoop-Darkatse
- AkariiinMKII/Scoop4kariiin
- TianXiaTech/scoop-txt
- rivy/scoop-bucket
- alextwothousand/scoop-bucket
- HUMORCE/nuke
- beer-psi/scoop-bucket
- littleli/Scoop-littleli
- mo-san/scoop-bucket
- BenjaminMichaelis/Config
- Toddli468/Pentest-Scoop-Bucket
- Small-Ku/turbo-bucket
- ShuguangSun/sgs-scoop-bucket
- WinApps-share/WinApps-bucket
- FlawlessCasual17/MyScoop
- The-Simples/scoop-minecraft
- natecohen/scoop-av
- KnotUntied/scoop-fonts
- babo4d/scoop-xrtools
- Deide/deide-bucket
- AkinoKaede/maple
- yuanying1199/scoopbucket
