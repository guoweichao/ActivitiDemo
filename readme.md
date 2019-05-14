##Activiti Demo 功能介绍

**环境**
1. SpringBoot 1.5.19.RELEASE
2. Activiti 6.0

**功能**
1. 自定义流程审批框架（通用配置）
2. 基于界面的流程配置（按钮配置，审批路径配置，流程状态配置）
3. 流程回退到上一节点
4. 流程挂起、激活
5. Activiti 获取流程图
6. 动态改变流程节点类型（普通节点 ——> 会签节点）Entity4Process
7. 动态调转流程节点，让流程跑到指定的节点（节点A -> 节点N（可以从一个节点任务变成多个节点任务））Entity5Process
8. 会签加签，减签 Entity6Process