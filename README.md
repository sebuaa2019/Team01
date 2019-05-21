# AIC智云农业
我们希望有专门的小车能够运行于农田，辅以物料网络，使这套系统能自动化地管理农田，实现农业管理精细化。

![核心设计](https://github.com/sebuaa2019/Team101/blob/master/media/%E6%A0%B8%E5%BF%83%E8%AE%BE%E8%AE%A1.png)

## 项目目录说明
| 目录 | 描述 |
| --- | --- |
| doc | 项目文档目录(文档工作是很丰富了) |
| src | 项目源代码 |
| src/Cloud | 云服务系统相关代码 |
| src/EdgeControlPlatform | 边缘控制平台相关代码 |
| src/Motor | 小车端运动相关代码 |
| src/Sensor | 小车传感器相关代码 |
| src/arm | 小车端机械臂控制相关代码 |

## 已有功能列表
| 功能名称 | 功能描述 |
| --- | --- |
| 自动巡航 | 小车在场地内自动巡航。|
| 植株识别 | 小车巡航过程中对植株进行检测，包括对植株分类，植株小类的识别。|
| 除草 | 用机械臂物理剪除杂草。|
| 施肥浇水 | 智能泵调度物料通过管道由机械臂配给给小车。|

## 未解决的问题
 - [ ] 自动巡航的地形识别功能不足，无法探测过低的地形问题。
 - [ ] 单目视觉信息不足以足够精细地控制机械臂。
 - [ ] 电力问题。
 
## 未来发展
 - [ ] 参加2019年冯如杯科技创新竞赛。
 - [ ] 参加2019年金砖国家专业技能竞赛。
 - [ ] 参加2019年大学生创新创业大赛。
 
## 开发人员
| 姓名 | 邮箱 | 主要工作 | 
| --- | --- | --- |
| 林家桢 | neo.jia.lin@outlook.com | PM，硬件维修，服务器运维。主要是打杂。 |
| 韩继开 | jikai_han@sina.com | 深度学习服务软件——图像识别。 |
| 段逸骁 | jamesdyx@buaa.edu.cn | 专门喊666 (实际上负责了Motor相关的开发和重要的组织安排工作。——ljz)|
| 杨帅 | yangshuai460@sina.com | demo摄影师，人工智能小车技术向主播，负责布置测试环境（耕地种草），维修机械臂，以及机械臂控制代码的编写|
