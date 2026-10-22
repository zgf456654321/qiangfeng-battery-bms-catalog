# Qiangfeng BMS & Battery PACK Product Documentation

**强风新能源科技（上海）有限公司**  
Qiangfeng New Energy Technology (Shanghai) Co., Ltd., China

BMS development, board supply and lithium battery PACK project enquiries for equipment manufacturers, PACK builders and system integrators. Project enquiries are coordinated in Shanghai; battery production and stock are coordinated with our Jiangxi factory. The selected version, supplied parts, dispatch location, lead time and validation scope are confirmed in the quotation.

This catalogue links to existing product photographs and project information. It is not a hardware/firmware source release or an online checkout.

## Contact / 采购联系

- Phone / 电话: **+86 19921917746**
- WeChat / 微信: **dream_zhu_**
- Business email: **[zgf004494@yeah.net](mailto:zgf004494@yeah.net)**
- [中文一页采购联系卡 / Chinese procurement contact card (PDF)](qiangfeng-bms-pack-supply-card-zh.pdf)
- [Company profile and enquiry links / 公司及询价入口](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/company)
- [中文产品目录](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/zh)
- [English catalogue](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/)
- [Company website / 公司官网](https://www.qiangfengsh.com/)

## 国内BMS与锂电池PACK采购目录

强风新能源科技（上海）有限公司开展BMS研发、板卡配套与锂电池PACK项目。上海负责研发与项目对接，电池生产及库存由江西工厂协调。面向全国设备厂家、PACK企业和系统集成商，按实际用途、型号与交付地区确认供货范围。

| 产品或项目 | 已公开的实物与型号 | 选型及采购入口 |
|---|---|---|
| 无人机6串BMS板组 | LYF6S20A，资料标称6串20A，主板、开关指示板及电芯连接板分别核对 | [6S板组原图与参数说明](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/uav-6s-bms) |
| 分布式BMS主控 | SHQF-MBMS V1.0原板，外部接触器、传感器、线束及固件另行确认 | [主控实拍与爱采购商品入口](https://www.qiangfengsh.com/product.html#verified-board-supply) |
| 电芯采集模块 | SHQF-CBMS V1.0，18串单板采集范围，核对电芯体系、线序、温度与主控配套 | [18串采集板实拍](https://www.qiangfengsh.com/product.html#verified-board-supply) |
| EMS储能控制板 | 公司原始实拍，BMS、PCS及外围设备接口与协议按项目确认 | [EMS实拍与采购说明](https://www.qiangfengsh.com/product.html#verified-board-supply) |
| 5至32串BMS系列 | 原板与采样线束照片，串数、电流与通信功能按所选版本确认 | [BMS系列与项目参数](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/5-32s-bms) |
| 2至4串电量计BMS | 现有BQ40Z50平台资料与SMBus方案，照片板型、固件和主机接口分别核对 | [电量计BMS原图与配套说明](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/fuel-gauge-bms) |
| 高压固定翼无人机电池项目 | 电池PACK、BMS主控与采集、PDU配电及CAN通信，按整机要求评估 | [民用无人机电池配套范围](https://www.qiangfengsh.com/drone-bms.html) |
| 锂电池PACK定制 | 电芯、BMS、结构、线束、通信与充电配套的供货边界 | [PACK项目与询价说明](https://www.qiangfengsh.com/battery-pack-custom.html) |
| AGV与机器人电池包 | 安装空间、任务节拍、持续与峰值负载、充电方式和主机协议 | [AGV及机器人电池项目](https://www.qiangfengsh.com/agv-robot-battery-pack.html) |

表中照片用于查看已有硬件与项目资料。板卡、线束、壳体、整组电池的供货范围分别确认；高压无人机方案的样机、整机集成、验证与适航配合范围另行约定。

询价请说明设备用途、电芯型号与串并联、电压容量、持续和峰值负载及时间、尺寸重量、主机通信、数量、交付城市和计划时间。电话 **19921917746**，微信 **dream_zhu_**，邮箱 **[zgf004494@yeah.net](mailto:zgf004494@yeah.net)**。

## 高压BMS主控、采集与系统配套 / High-voltage BMS selection

面向储能PACK企业和设备集成商，强风提供高压BMS项目对接。下面按已核对的规格资料区分主控、采集和系统总控，采购时明确所需层级及供货清单。

| 单元 / Unit | 资料型号与范围 / Documented reference | 报价需确认 / Quotation inputs |
|---|---|---|
| BCU主控 / Battery controller | **BCU-B24-01**：电池数据汇总、状态告警与控制；CAN、RS485及PCS/EMS接口配套 | 传感器、继电器、线束、接口与固件版本 |
| BMU采集 / Cell-monitoring module | **BMU-B18**：资料配置为单板**4至18串**，温度采集、被动均衡与**isoSPI**菊花链 | 电芯体系、单板串数、模块数量、线序与主控配套 |
| BAU系统总控 / System-level controller | 三级BMS系统的数据汇总及对外接口，协调主控、采集及上层设备 | 具体型号、系统规模、PCS/EMS通信与固件逐项确认 |

These are separate controller and acquisition references. The BMU's 4–18-cell range is per module, not the series count of the complete battery system. Define the cell chemistry, module count, system voltage, host protocol and required supplied parts before quotation.

[查看官网高压BMS选型与项目说明 / Company selection information](https://www.qiangfengsh.com/product.html)

上面的规格系列与本目录SHQF-MBMS、SHQF-CBMS实拍板卡分别选型，不将照片与其他系列的额定电压、电流或接口直接对应。高压绝缘、保护、PDU和整机验证按项目确认；板卡资料不代表整机验证或适航批准。

**项目联系 / Project enquiries:** 电话 **+86 19921917746** · 微信 **dream_zhu_** · 邮箱 **[zgf004494@yeah.net](mailto:zgf004494@yeah.net)**。

## BMS and PACK references / 产品与项目资料

| Reference | Supply scope and original photographs |
|---|---|
| [LYF6S20A 6S UAV BMS](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/uav-6s-bms) | BMS board set, switch and indicator references. Board supply is distinct from a complete battery PACK. |
| [High-voltage BMS and EMS](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/high-voltage-bms-ems) | Controller, cell-acquisition and EMS board references. Required components and host interfaces are confirmed per project. |
| [Civil high-voltage UAV battery project](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/high-voltage-uav-battery) | PACK, BMS, PDU and CAN requirements, installation and validation scope. Aircraft integration and airworthiness approval are separate project responsibilities. |
| [Relay-control BMS](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/relay-control-bms) | Existing board and battery-enclosure photographs. Switching, wiring and PACK scope must be specified. |
| [Fuel-gauge BMS](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/fuel-gauge-bms) | Existing hardware reference and version/interface matching for a battery project. |
| [5–32S BMS project support](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/5-32s-bms) | Board, chemistry, voltage, current and communication requirements matched to the selected version. |
| [48V PACK assembly reference](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/48v-pack-project) | Historical 2024 photographs of BMS, modules and wiring, not a promise of identical current stock. |
| [USB / Bluetooth tool](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/usb-bluetooth-tool) | Original interface-tool photographs and equipment/software version matching. |

![Qiangfeng high-voltage BMS controller and cell-acquisition boards. These are components, not a complete aircraft battery PACK.](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/bms-high-voltage-original.jpg)

![Original LYF6S20A 6S UAV BMS board-set photograph, a separate product line from the high-voltage BMS above.](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/uav-6s-bms-original.jpg)

## Starlink Mini-compatible battery kits

Independently supplied compatible batteries with a matched charger and user manual. The terminal, satellite-service subscription and solar panel are not included in the base kit.

| Model | Nominal voltage | Rated capacity | Kit reference retail price (CNY) | Online enquiry / 询价（预填型号） |
|---|---:|---:|---:|---|
| LIFIRST-HB-99 | 18V | 5.5Ah / 99Wh | 765  [99Wh: enquire and confirm shipping](https://docs.google.com/forms/d/e/1FAIpQLSdx-mG3j-H6vrwYWqhMdXxItm-YVLeJKHv8Wl00nBteDbP6xw/viewform?usp=pp_url&entry.1964661460=LIFIRST-HB-99%20%2F%2018V%2099Wh%20battery%20%2B%20matched%20charger%20kit) |
| LIFIRST-HB-158 | 18V | 8.8Ah / 158Wh | 934  [158Wh: enquire and confirm shipping](https://docs.google.com/forms/d/e/1FAIpQLSdx-mG3j-H6vrwYWqhMdXxItm-YVLeJKHv8Wl00nBteDbP6xw/viewform?usp=pp_url&entry.1964661460=LIFIRST-HB-158%20%2F%2018V%20158Wh%20battery%20%2B%20matched%20charger%20kit) |
| LIFIRST-HB-180 | 18V | 10Ah / 180Wh | 947  [180Wh: enquire and confirm shipping](https://docs.google.com/forms/d/e/1FAIpQLSdx-mG3j-H6vrwYWqhMdXxItm-YVLeJKHv8Wl00nBteDbP6xw/viewform?usp=pp_url&entry.1964661460=LIFIRST-HB-180%20%2F%2018V%20180Wh%20battery%20%2B%20matched%20charger%20kit) |
| LIFIRST-HB-200 | 18V | 11Ah / 200Wh | 1,064  [200Wh: enquire and confirm shipping](https://docs.google.com/forms/d/e/1FAIpQLSdx-mG3j-H6vrwYWqhMdXxItm-YVLeJKHv8Wl00nBteDbP6xw/viewform?usp=pp_url&entry.1964661460=LIFIRST-HB-200%20%2F%2018V%20200Wh%20battery%20%2B%20matched%20charger%20kit) |

The online links prefill the selected battery model and matched-charger kit. **Add your quantity to the first answer, then complete the destination and reply details.** This is an enquiry, not an order or payment. You may also use the existing email enquiry below.

在线表单会带入所选型号和带充电器套装；请在第一项补充数量，再填写目的地与回复方式。此为询价，不是下单或付款；也可使用下方邮件入口。

These China-origin kit reference prices **exclude freight**. A compatible 60W 36V folding solar panel is an optional accessory at CNY299, subject to version and availability confirmation. It is not included by default. Wholesale and destination-specific quotations are confirmed separately.

Operating time varies with terminal load, settings, battery state and conditions; no fixed runtime is guaranteed. Exact charger specifications and packed shipping weight must match the dispatched version. Model-specific test documents, carrier acceptance, destination import conditions, warehousing, last-mile delivery, returns and marketplace permission are separate checks. No approved TikTok battery route or worldwide delivery is implied by this catalogue. Shipping and after-sales conditions must be confirmed before an order is accepted.

These are third-party compatible accessories, not official Starlink or SpaceX products, and are not affiliated with, endorsed by or sponsored by Starlink or SpaceX.

[Four-capacity battery page and enquiry inputs](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/starlink-mini-battery)

### Real installation demonstration / 实物安装演示

<a href="https://www.qiangfengsh.com/international.html#battery-installation"><img src="https://qiangfeng-battery-bms.zgf004494.chatgpt.site/battery-installation-poster-original.png" alt="Original Qiangfeng compatible-battery installation, button and indicator demonstration" width="240"></a>

Watch 14.8 seconds of original manufacturer footage showing fitting, the power button and the indicator. The silent demonstration is a series reference; confirm the selected capacity and hardware version in the quotation. It is not a runtime or network-connectivity test.

查看真实安装、按键与指示灯演示，再对照上表选择容量。视频展示同系列硬件；具体容量、供货版本和随配充电器在报价中确认。

- [Watch the original demonstration on Qiangfeng’s company website / 官网实物演示](https://www.qiangfengsh.com/international.html#battery-installation)
- [View the four charger-included kit quotes and supplier phone / 爱采购四容量报价与商家电话](https://b2b.baidu.com/land/e2ee5658716f3f6532efc389ae691b01)
- [Request a capacity and destination quotation / 提交容量与目的地询价](mailto:zgf004494@yeah.net?subject=Battery%20kit%20and%20destination%20quote&body=Capacity%3A%0AQuantity%3A%0ADestination%20country%20and%20city%3A%0APostcode%3A%0ACharger%20plug%3A%0ARetail%20or%20wholesale%3A%0A)

These are enquiry links. Battery carriage, destination requirements, total delivered price and returns are confirmed before accepting an order.

## Quotation inputs / 询价资料

For a BMS or PACK project, send the application, cell chemistry/model and series/parallel configuration, voltage and energy, continuous/peak current and duration, installation dimensions and weight limit, host communication/CAN protocol, required supply scope, quantity, destination city/country and requested delivery date. State whether you need boards, wiring or a complete battery PACK.

BMS/PACK项目请说明用途、电芯型号和串并联、电压容量、持续与峰值电流及时间、尺寸重量限制、主机通信协议、供货范围、数量、交付地区及计划时间。请明确采购板卡、配套部件，还是整组电池。

For a compatible battery enquiry, specify capacity, quantity, required accessories and destination. We confirm the selected version, lawful delivery route, total quotation and return arrangements before accepting the order.

## Sources and document status

- [Company and public product facts](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/company)
- [Plain-text company/product index](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/llms.txt)
- [Four battery model references checked against 2026 transport documents](https://www.qiangfengsh.com/international.html#battery-document-review) — model references, not carrier or marketplace approval.
- [Current public product guide](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/qiangfeng-product-guide-2026-10.pdf)
- [Published 6S UAV BMS procurement brief](https://qiangfeng-battery-bms.zgf004494.chatgpt.site/qiangfeng-lyf6s20a-procurement-brief.pdf)

Updated: **22 October 2026**. Photographs identify existing company hardware and historical project references. This repository does not grant a hardware, firmware, patent or certification licence. Availability, specifications and commercial terms are confirmed for the selected project and version.
