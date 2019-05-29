# opensips + rtpengine as SBC

## 需求背景
已有SIP server 服务器以及 运营商的接入系统， 可以在内网中通过软电话或标准的SIP电话注册使用， 现有需求要在外网中通过web浏览器接入已有SIP server并且能与普通的sip电话或普通电话通话。

研究结果： 由于各种原因在虚拟机上，在内网中 可以使用web端电话正常拨打和接听电话， 外网因为安全和成本原因未做检验，但通过大量学习和了解得出了解决方案，但未做实践。

[opensips + rtpengine as SBC(一)](https://github.com/forjuan/SBC-opensips-rtpengine/blob/master/docs/1.md)