# LASER.TX

<el-tag effect="plain">SKU:U066</el-tag>

<div class="product_pic"><img src="assets\img\product_pics\unit\laser_tx\unit_laser_tx_01.webp"><img src="assets\img\product_pics\unit\laser_tx\unit_laser_tx_02.webp"></div>

## Description

***LASER.TX*** is one of the communication devices among the M5Units family - a Laser emitter with adjustable focal length.

It is mainly built with a laser diode Laser communications devices are wireless connections through the atmosphere. They work similarly to fiber-optic links, except the beam is transmitted through free space. While the transmitter and receiver must require line-of-sight conditions, they have the benefit of eliminating the need for broadcast rights and buried cables.

Laser communications systems can be easily deployed since they are inexpensive, small, low power and do not require any radio interference studies.
Two parallel beams are needed, one for transmission and one for reception therefore we have a LASER.RX in parallel.  


*warning!!! laser is dangerous for human being, Don’t aim a laser pointer towards a person’s head. This is to prevent the beam from getting in their eyes, possibly causing eye damage. Remember that people can move unexpectedly, so keeping away from their heads is a good idea*

## Product Features

- Laser transmitter
- adjustable focal length
- Work voltage: 5V
- Pair with LASER.RX
- Two Lego-compatible holes
- Program Platform: Arduino, UIFlow(Blockly, Python)

## Include

- 1x LASER.TX unit
- 1x GROVE cable

## Applications

- Laser communication system on space.

## Specification

<table>
   <tr style="font-weight:bold">
      <td>Resources</td>
      <td>Parameter</td>
   </tr>
   <tr>
      <td>Operating Voltage</td>
      <td>5V</td>
   </tr>
   <tr>
      <td>Net weight</td>
      <td>5g</td>
   </tr>
   <tr>
      <td>Gross weight</td>
      <td>19g</td>
   </tr>
   <tr>
      <td>Product Size</td>
      <td>32*24*8mm</td>
   </tr>
   <tr>
      <td>Package Size</td>
      <td>60*57*17mm</td>
   </tr>
</table>

## EasyLoader

<img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/EasyLoader_logo.webp" width="100px" style="margin-top:20px">

<a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Unit/LASER/EasyLoader_LASER_TX.exe"><el-button type="primary">download EasyLoader</el-button></a>

>1.EasyLoader is a simple and fast program burner. Every product page in EasyLoader provides a product-related case program. It can be burned to the master through simple steps, and a series of function verification can be performed. .

>2. After downloading the software, double-click to run the application, connect the M5 device to the computer through the data cable, select the port parameters, click **"Burn"** to start burning. (**For M5StickC burning, please Set the baud rate to 750000 or 115200**)

>3. Currently EasyLoader is only suitable for Windows operating system, compatible with M5 system adopts ESP32 as the control core host. Before installing for M5Core, you need to install CP210X driver (you do not need to install with M5StickC as controller)[Click here to view the driver installation tutorial](en/related_documents/M5Burner#install-usb-driver)

## Schematic

<img src="assets/img/product_pics/unit/laser_tx/unit_laser_tx_04.webp" width="50%" height="50%">

### Pin Map

<table>
 <tr><td>M5 PORTB</td><td>GPIO36</td><td>GPIO26</td><td>5V</td><td>GND</td></tr>
 <tr><td>LASER_TX</td><td>/</td><td>TX</td><td>5V</td><td>GND</td></tr>
</table>

## Example

### 1. Arduino

- [Click here to download the Arduino example](https://github.com/m5stack/M5Stack/tree/master/examples/Unit/LASER)

### 2. UIFlow

<img src="assets/img/product_pics/unit/laser_tx/laser-tx.webp">

<el-divider content-position="right">Last updated: 2020-12-14</el-divider>

<script>

   var purchase_link = 'https://m5stack.com/collections/m5-unit/products/laser-tx-unit';

   anchor_search(purchase_link);
   scrollFunc();

</script>
