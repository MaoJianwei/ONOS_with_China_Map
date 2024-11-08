# ONOS with China Map

Add China geography map to ONOS Web GUI as a background for network topology.

.

**Notes:** This project have been published at the **[ONOS_TopologyShow_ChineseMap](https://github.com/MaoJianwei/ONOS_TopologyShow_ChineseMap)** project, with CI/CD support, providing the Docker image. (2024.09.16)

.

## Statement

**Attention! This map is not accurate, and is only used as a rough example or demonstration.**

**For the standard and accurate China map, you must refer to web site of Chinese government, such as [http://www.gov.cn/](https://www.gov.cn/)**

.

![https://raw.githubusercontent.com/MaoJianwei/ONOS_with_China_Map/master/Screenshot.png](https://raw.githubusercontent.com/MaoJianwei/ONOS_with_China_Map/master/Screenshot.png)

![https://raw.githubusercontent.com/MaoJianwei/ONOS_with_China_Map/master/Screenshot.png](https://raw.githubusercontent.com/MaoJianwei/ONOS_with_China_Map/master/demo-screenshoot-multiple-links.png)
.

## ONOS Gerrit

This commit was originally uploaded to ONOS code base in 2018.03.26, [https://gerrit.onosproject.org/c/onos/+/17607](https://gerrit.onosproject.org/c/onos/+/17607)

## Change logs

1. Make and add a China geography map, which is built by QGIS software.

>* The public source of the map image is [www.gov.cn](https://www.gov.cn/) website.

2. Add the index of map to UiExtensionManager.java

>* *$ONOS_ROOT/web/gui/src/main/java/org/onosproject/ui/impl/UiExtensionManager.java*

Signed-off-by: Jianwei Mao <maojianwei2012@126.com>
