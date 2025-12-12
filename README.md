# Detachable 18650 Pwrbank
<!--<img width="536" height="228" alt="image" src="https://github.com/user-attachments/assets/9dac390e-52f9-44d5-825d-28c0b896d68c" />-->
<img alt="image" src="https://raw.githubusercontent.com/ResAlexander/detachable-18650-pwrbank/refs/heads/main/PCB_PCB_2025-12-12.png" />
## English Version Below

一个可以将单节（可拆卸）18650锂电池变成行动电源的模块，并预留了2.54mm的外设接口，不支持PD快充。

### 💻 特性：
 - 预留电池电流检测功能。
 - 2输入+3输出，非常便于使用。
 - 拓展排针提供稳定放置功能，并预留外设接口。
 - 封装不小于0603，便于手工焊。还嫌小的话用热风枪。
 - 可以便捷地设置充电电流（不要把用于设置电流的短路帽接到外置电池端口，这是绝对错误的。）
 - 支持外接带2.54mm端子的电池。（当心！千万别接反了）
 - 电路板看着很有食欲。

### 🟨 注意：
ETA9742采用同口输入/输出。这意味着，「输入」「输出」本质上是双向口；USB和Type-C输入端口，在电气上是可以输出的。
 - 如果需要边充边放（例如 充电器-本电源模块-你的手机），
   请先将本充电宝连接到充电器，再把你的负载（手机）放上去。
 - 同样，手机可能会反向给充电宝供电（特别是开启OTG时）。
 - 指示灯可以明确反映充放电状态。

### ⚠ 警告：
1. 不准短路，特别是外置电池连接端口。
2. 不要无人充电。
3. 确认使用的电池品质，并确保充放电倍率不超过1C（动力电池的话3C）。

### Features:
 - Ibat detection is reserved.
 - With 2 inputs and 3 outputs, it's very easy to use.
 - Expansion receptacles provide stable placement and reserve interfaces for external devices.
 - The package size is at least 0603 for easy manual soldering. Use a hot air gun if tou think it's still too small.
 - The charging current can be easily set (DO NOT connect the shorting cap used to set the current to the external battery port; That's 1000% WRONG.)
 - Supports external batteries with 2.54mm terminals. (DO NOT connect in Reverse polarity!)
 - That PCB looks appetizing

### Note:
 - ETA9742 uses the same port input and output. That means the inputs and outputs are actually bidirectional; These inputs can also be outputs electrically speaking.
 - If you require simultaneous charging and discharging (e.g., charger -> this power module -> your mobile phone), please first connect this power module to the charger, and then connect your load (mobile phone).
 - Similarly, a phone may reverse-power a power bank (especially when OTG is enabled).
 - Indicators clearly show the charging/discharging status.


### Warning:
1. No short-circuit. Especially "External Bat Connector".
2. Avoid charging the device unattended.
3. Verify the quality of the batteries used and ensure the charge and discharge rate does NOT exceed 1C (3C for power batteries).
