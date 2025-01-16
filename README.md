Apache-HertzBeat open source real-time monitoring system has a default password vulnerability

HertzBeat is an open source real-time monitoring system that does not require an agent, has a performance cluster, is compatible with Prometheus, and has the ability to build custom monitoring and status pages. HertzBeat's powerful customization, multi-type support, high performance, and easy expansion hope to help users quickly build their own monitoring systems. HertzBeat (HertzBeat) open source real-time monitoring system has a default password vulnerability.
fofa
app="HertzBeat-Real-time Monitoring System"

poc
Default account password admin/hertzbeat

Account password written into the system hard-coded

Vulnerability reproduction
1. http://121.40.193.124:32769/
Successfully logged in using the default account password

2. http://51.141.173.144/
Successfully logged in using the default account password

3. https://hertz.solochex.com/
Log in successfully using the default account and password

Other cases:
https://hertz.solochex.com/
http://izihao.cn:1020/
http://47.108.228.164:7010/
https://monitor-hert.dituhui.com/
https://hertzbeat.mesh-asia.com/
http://8.134.136.162:9100/
http://47.108.201.158:8157/
http://124.221.7.12/
https://47.102.123.25/
