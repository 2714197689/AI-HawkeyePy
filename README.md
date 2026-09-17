# AI-HawkeyePy
夜鹰是用 Python 实现的 Windows 应急响应工具，单文件   EXE，用于主机疑似被入侵后的现场采集：一次采全进程、服务、任务、启动项、账号、外连、日志与 YARA，约 40   秒完成，由规则引擎标为 low 或 suspicious 两档，每条附 risk_reason 供复核。规则可扩展是其主要特征——内置规则固定为   module、risk、reason、when 四段，支持十余种操作符并可用 func 调系统 API，用户还能在 userskills/ 目录用 YAML   改规则，无需改代码。AI 只做辅助、不下入侵结论，分 off、local、auto   三档，失败自动回退本地摘要；另有对话面板 King，具备工具调用与记忆能力。
