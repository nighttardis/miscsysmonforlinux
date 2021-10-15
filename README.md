# sysmonforlinux
Misc Files for [sysmonforlinux](https://github.com/Sysinternals/SysmonForLinux)

## sysmon.rsyslog.conf
Simple rsyslog config to strip off sysmonforlinux logs and send them to their own log file(/var/log/sysmon.log) instead of going to /var/log/syslog. This will keep /var/log/syslog cleaner as well as provide better rotation support.

Place file in /etc/rsyslog.d

## sysmon.logrotate
Simple logrotate to handle rotating log file created by sysmon.rsyslog.conf

Place file in /etc/logrotate.d
