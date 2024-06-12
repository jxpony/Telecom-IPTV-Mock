# 长春电信IPTV机顶盒模拟器

本仓库模拟了长春电信IPTV机顶盒的登陆流程，可以自动获取频道的组播播放列表、单播播放列表和节目单

## 使用前必读

本仓库代码旨在提供一种家庭自动化的思路，本仓库的代码仅供个人测试使用，并不保证在其他用户的使用环境下的功能完善。

## 更新日志

20240612:

- 添加 crontab 表达式环境变量，容器将后台运行，并按照预定义的 crontab 表达式运行实际的抓取程序。

20221108:

- 在生成播放列表之前先根据 `UserNumber` 进行排序

20221102：

- 添加docker镜像

20221022：

- 第一版，功能运行基本正常，代码结构混乱，暂无使用说明。

## TODO

- 代码结构优化
- 使用更好的节目单替代

## 申明

当你查阅、下载了本项目源代码或二进制程序，即代表你接受了以下条款

- 本项目和项目成果仅供技术，学术交流和Python3性能测试使用
- 本项目贡献者编写该项目旨在学习Python3 ，提高编程水平
- 用户在使用本项目和项目成果前，请用户了解并遵守当地法律法规，如果本项目及项目成果使用过程中存在违反当地法律法规的行为，请勿使用该项目及项目成果
- 法律后果及使用后果由使用者承担
- [GPL LICENSE](https://github.com/vergilgao/Telecom-IPTV-Mock/blob/master/LICENSE)
- 若用户不同意上述条款任意一条，请勿使用本项目和项目成果
