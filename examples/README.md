# Examples
包括了QPM的各个典型应用场景。

## Process 基本进程管理
* qpm_daemon.php	使用QPM 编写daemon程序。
* qpm_simple_daemon.php	使用QPM 编写daemon程序。
* fork_by_callable.php	fork 的使用示例。
* to_background.php 将进程转入后台的示例。

## Supervisor 进程监控（进程树管理）
* multi_group_supervision.php	MultiGroupOneForOne模式进程监控（进程树管理）的使用示例。
* one_for_one_supervision.php	OneForOne模式进程监控（进程树管理）的使用示例。
* spider_task_factory.php	TaskFactoryMode模式进程监控（进程树管理）的使用示例。spider_task_factory_data.txt是其数据文件。
* task_factory.php TaskFactoryMode模式进程监控（进程树管理）的使用示例。

## PID PID文件管理
* pid_check.php	和 pid_main.php	基于qpm\pid\Manager 管理和使用PID文件。

## Log 日志
* use_log.php 使用日志的例子。
