# Priviledge-Escalation

## MSF 利用enum_patches模块 收集补丁信息，列出可能存在的漏洞
(必须已在目标机器上获取到了一个Meterpreter session,需要将现有的Meterpreter session调到后台运行)
- use post/windows/gather/enum_patches
- show options
- set session 1
- run
