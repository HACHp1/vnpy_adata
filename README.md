# VeighNa框架的AData数据服务接口

<p align="center">
  <img src ="https://vnpy.oss-cn-shanghai.aliyuncs.com/vnpy-logo.png"/>
</p>

## 说明

基于[adata](https://github.com/1nchaos/adata)开发的vnpy数据接口：

## 安装

安装环境推荐基于3.0.0版本以上的【[**VeighNa Studio**](https://www.vnpy.com)】。

下载源代码后，解压后在cmd中运行：

```
pip install .
```

## 使用

在 C:\\Users\\xxx\\.vntrader\\vt\_setting.json 的 vnpy 配置文件中修改：

```json
{"datafeed.name": "adata"}
```

之后直接使用vnpy引擎即可。

* 股票标的举例：`"600519" #  贵州茅台`；
* 指数标的举例：`"ind-000001" #  上证指数`。
