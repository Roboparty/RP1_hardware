# RP1 机械设计

[项目首页](../README_CN.md) · [整机 BOM](../04_BOM/README.md)

本目录提供 RP1 的机械设计源文件、Parasolid 整机模型、工程图和制造文件。各配置的物料数量见整机 BOM，材料与表面处理要求见工程图和 CMF 规格表。

![RP1 正面、侧面与背面视图](../assets/images/robot-overview.png)

## CAD 下载

| 文件包 | 内容 |
| --- | --- |
| [RP1_SolidWorks_Source.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_SolidWorks_Source.zip) | SolidWorks 装配体与零件源文件 |
| [RP1_Parasolid_Model.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Parasolid_Model.zip) | Parasolid 整机模型（.x_t） |
| [RP1_Drawings.zip](https://github.com/Roboparty/rp1_hardware/releases/download/v0.1.0/RP1_Drawings.zip) | 可编辑 SolidWorks 工程图（.SLDDRW） |

完整解压源文件包，从 `RP1_SolidWorks_Source/RP1.3.4整机.SLDASM` 打开整机，保留包内文件位置。编辑工程图时，将 `RP1_Drawings` 内的 `.SLDDRW` 文件放到对应源模型所在目录。各文件包包含许可说明，第三方文件保留原有条款。

## 制造文件

加工 BOM 按料号汇总单机用量，5DOF、7DOF 分列，均对应运控头配置。

| 工艺 | BOM 与文件 | 材料与表面处理 |
| --- | --- | --- |
| CNC 加工 | [加工 BOM](02_Manufacturing/01_CNC/RP1_CNC_BOM.xlsx)、[通用件](02_Manufacturing/01_CNC/Common/)、[5DOF](02_Manufacturing/01_CNC/5DOF/)、[7DOF](02_Manufacturing/01_CNC/7DOF/) | [CMF 规格表](02_Manufacturing/01_CNC/CMF说明/RP1_CNC_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/01_CNC/CMF说明/) |
| 3D 打印 | [加工 BOM](02_Manufacturing/02_3D_Printing/RP1_3D_Print_BOM.xlsx)、[STEP 模型](02_Manufacturing/02_3D_Printing/STEP_3D模型/) | [CMF 规格表](02_Manufacturing/02_3D_Printing/CMF说明/RP1_3D_Print_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/02_3D_Printing/CMF说明/) |
| 橡胶件 | [加工 BOM](02_Manufacturing/03_Rubber/RP1_Rubber_BOM.xlsx)、[STEP 模型](02_Manufacturing/03_Rubber/STEP_3D模型/) | [CMF 规格表](02_Manufacturing/03_Rubber/CMF说明/RP1_Rubber_CMF_Specification.xlsx)、[CMF 说明](02_Manufacturing/03_Rubber/CMF说明/) |

文件名中的料号和修订后缀用于对应图纸与模型。
