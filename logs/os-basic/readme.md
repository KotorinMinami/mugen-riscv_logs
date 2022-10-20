# 对os-basic logs的初步分析

## 可修改脚本的fail例
- oe_test_kernel_module_operation
- oe_test_system_log_view

## 系统自身问题
- yum源内没有对应软件或依赖 ：[lost_in_yum](./list_and_details/lost_in_yum.list) 共29个样例
- 系统内核不支持对应服务 ：oe_test_kernel_kdump 1个样例
- 需要加载网卡配置 ： [local_eth_need](./list_and_details/local_eth_need) 共15个样例
- 需要ssh连接远程机器 ： [ssh_need](./list_and_details/ssh_need) 共15个样例
