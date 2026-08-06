# Bi-directional Power Meter

![IM-4190](assets/img/IM4190%20meter.gif)

## The Idea
As a professional I designed IoT RF products, mostly 870MHz and higher. As a licensed HAM operator I use Software Defined Radio (e.g., ADI Pluto) and had commercial rig's from Yeasu and Kenwood.

One thing that was missing was a **Bird**, **HP** or **R&S** like Power Meter. Most surplus meters are without the measurement head/probe as these are costly and easy to blow up (attenuation first!).

![nrvz](assets/img/rs-nrvz.png)

Already build systems that used the AD8307 for power measurement up to 500MHz. Also used the AD8302 to build a VNA like sensor for soil impedance measurements. So why not build my own power meter.

## Measurement Bridge
To measure the forward and backward power a stripline pickup at both sides of a PCB could be used.

![vk5ajl](assets/img/coupler(vk5ajl).png)


 But this time I use Mini-Circuits **ZFDC-10-2-S** 10-1000MHz 10dB Directional Couplers.

![ZFDC-10-2-S](assets/img/mini-circuits.png)

### Bi-directional Bridge

By combining two Mini-Circuits `ZFDC-10-2-S` I have my measurement bridge with higher quality than D-I-Y.

![bridge](assets/img/bi-directional.png)

_**\<to be continued...\>**_

