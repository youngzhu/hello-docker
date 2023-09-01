## 1. kibana: No Living connections error
也不知道改了啥，改了试，试了改，重复了好多次。最后将 localhost 改成 es 居然就好了。

结论：URL里不能用 localhost （原因未知）

猜测：可能是 docker-compose 的版本问题，据说，版本2和3的差别很大