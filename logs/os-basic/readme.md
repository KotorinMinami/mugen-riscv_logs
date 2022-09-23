# 对os-basic logs的初步分析

## 系统版本问题
- RTC时间检测失败 （test_date）

## 脚本问题
- 脚本中check_free_disk函数无法获取硬盘信息（test_disk_schedule共2项）
- 脚本中参数可能配置，参数错误（test_basic_set_account，kernel_cgroup)

## 系统自身问题
- 安装软件失败（怀疑依赖被清除或源中无该软件包）（例 pciutils,dmidecode,tuned,kexec-tools,grub2-tools,powertop)
- 系统的service配置有问题（系统本身问题or测试套清除时与环境冲突）


- 具体原因待分析
