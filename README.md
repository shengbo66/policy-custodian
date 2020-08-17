# policy-custodian
policy for custodian

在AWS中国区，resource group还没有部署。为了方便对Tag的管理，可以使用 custodian 工具。本项目是准备了针对各种资源类型的添加Tag的Policy实例文件，供参考。即便将来resource group进入中国区，custodian也可以作为一个额外的选择。
目前已经就绪的资源类型包括：
EC2
Lambda
S3 bucket

项目在摸索阶段，也请有兴趣的builder提供建议，帮助完善
