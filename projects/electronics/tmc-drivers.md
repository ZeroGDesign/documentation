---
description: An informative list to help you choose the drivers for your project.
---

# TMC Drivers

{% hint style="warning" %}
This is **NOT** an exhaustive list, please refer to the relevant documentation and manuals for the drivers of your choice.  This page serves merely as a pointer to picking out your hardware.
{% endhint %}

***

### <mark style="color:red;">BTT 5160T Plus</mark>

10.6A RMS | 60V | SPI

{% hint style="danger" %}
Note: To get the full performance out of these drivers, you need to swap the **physical** sense resistor on the board, this is not an operation for beginners.
{% endhint %}

<details>

<summary>More Info</summary>

<table><thead><tr><th width="180"></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td>Driver Chip</td><td>TMC5160-TA</td><td></td></tr><tr><td>Driver Voltage</td><td>8-60v</td><td></td></tr><tr><td>Max RMS</td><td>10.6A </td><td></td></tr><tr><td>Operating Mode</td><td>SPI</td><td></td></tr><tr><td>Sense Resistor</td><td>0.022</td><td></td></tr></tbody></table>

</details>

***

### <mark style="color:red;">BTT 5160T & Pro</mark>

3A | 36V 5160T | 56V 5160Pro | SPI

{% hint style="success" %}
Good for chasing performance, high voltage and current limits
{% endhint %}

<details>

<summary>More Info</summary>

<table><thead><tr><th width="180.5"></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td>Driver Chip</td><td>TMC5160-TA</td><td></td></tr><tr><td>Driver Voltage</td><td>8-36v (5160T) | 8-56v (5160 Pro)</td><td></td></tr><tr><td>Max RMS</td><td>3.0A</td><td></td></tr><tr><td>Operating Mode</td><td>SPI</td><td></td></tr><tr><td>Sense Resistor</td><td>0.075</td><td></td></tr></tbody></table>

</details>

***

### <mark style="color:red;">BTT 2240</mark>

2.1A | 36v | SPI

{% hint style="success" %}
The 2240's have an integrated thermistor that can be displayed.
{% endhint %}

<details>

<summary>More Info</summary>

<table><thead><tr><th width="179"></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td>Driver Chip</td><td>TMC2240-ATJ</td><td></td></tr><tr><td>Driver Voltage</td><td>4.5-36v</td><td></td></tr><tr><td>Max RMS</td><td>2.1A</td><td></td></tr><tr><td>Operating Mode</td><td>SPI</td><td></td></tr><tr><td>RREF</td><td>12000</td><td></td></tr></tbody></table>

</details>

***

### <mark style="color:red;">BTT 2209</mark>

2.0A | 28V | SPI / UART

{% hint style="success" %}
Good for beginners, easy to set up.
{% endhint %}

<details>

<summary>More Info</summary>

<table><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td>Driver Chip</td><td>TMC2209-LA</td><td></td></tr><tr><td>Driver Voltage</td><td>5.5-28v</td><td></td></tr><tr><td>Max RMS</td><td>2.0A</td><td></td></tr><tr><td>Operating Mode</td><td>SPI | UART</td><td></td></tr><tr><td>Sense Resistor</td><td>0.110</td><td></td></tr></tbody></table>

</details>



{% include "../.gitbook/includes/btt-kraken.md" %}

