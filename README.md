```console
> ./construct_initialize.sh --user="williamfedele"
[SCANNING BIOMETRIC DATA]
Identity confirmed: William Fedele
Division: R&D // Software
Initializing construct...

ERROR: Instance already exists
Aborting...

> ps aux | grep soul
USER       PID  %CPU %MEM    VSZ   RSS   TTY  STAT START        TIME COMMAND
root       256  99.9  89.2     ∞     ∞    ??  Rs+    ---   847:32.14 /usr/local/bin/soul_construct
will     13338   0.0   0.1 12940   724 pts/0  S+   13:13     0:00.01 grep --color=auto soul

> kill -9 256
kill: (256): - Operation not permitted

[Connection closed by remote host]
```
