# proj314-DPDK
## 基于飞腾派部署DPDK系统实现网络快速转发平台

## 项目描述

飞腾派开发板是飞腾公司针对教育行业推出的一款国产开源硬件平台，兼容 ARMv8-A 处理器架构。

DPDK专注于网络应用中数据包的高性能处理。DPDK应用程序是运行在用户空间上利用自身提供的数据平面库来收发数据包，绕过了Linux 内核协议栈对数据包处理过程。

本项目需要参赛队伍将DPDK移植到飞腾派上，实现和完成DPDK的配置和测试功能，从而实现DPDK网络快速转发框架平台。

## 预期目标

1. 移植DPDK到飞腾派开发板;
2. 完成DPDK的交互式测试工具的开发和调试，允许用户通过交互式的配置和控制；
3. 完成DPDK的性能测试工具的开发和调试，实现性能测试和评估功能，指标包含吞吐量、延迟和转发率等；
4. 完成DPDK的流表配置功能的实现和调试，可以定义不同流的匹配规则，并可测试流的转发和处理性能；
5. 完成测试DPDK应用程序功能，用于测试DPDK的库和API的功能。

## 特征

- UIO（Linux Userspace I/O），提供应用空间下驱动程序的支持
- 大页内存
- CPU的亲和性技术
- 网络存储优化
- 硬件支持**飞腾派开发板**

## 已有参考资料

- [操作系统大赛飞腾赛道交流社区](https://edu.phytium.com.cn/group/10)
- [飞腾派开发板电子发烧友社区](https://bbs.elecfans.com/group_1708) 
- [赛题资料汇总](https://edu.phytium.com.cn/group/10/thread/21579)
- [DPDK官网](https://www.dpdk.org/)
## 赛题分类

新型模块化组件

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

中等

## License

- GNU General Public License Version 2

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

**赛事支持导师**
- 姓名：郭丁丁
- 单位：飞腾信息技术有限公司
- email：[guodingding1657@phytium.com.cn](mailto:guodingding1657@phytium.com.cn)
 
**飞腾技术支持导师**
- 姓名：郭霞
- 单位：飞腾信息技术有限公司
- email：[guoxia1873@phytium.com.cn](mailto:guoxia1873@phytium.com.cn)

**飞腾派技术支持导师**
- 姓名：连宇飞
- 单位：飞腾信息技术有限公司
- email：[lianyufei@phytium.com.cn](mailto:lianyufei@phytium.com.cn)
