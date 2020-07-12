# hackintosh-MSI-GF63 

Model: https://www.msi.com/Laptop/support/GF63-THIN-9SC.  <br>
Motherboard: Intel chipset HM370. <br>
Nhà sản xuất:	MSI. <br>
CPU:	Intel Core i5. <br>
Loại CPU:	9300H  <br>
Tốc độ CPU:	2.40 GHz  <br>
Bộ nhớ đệm:	8MB cache  <br>
Tốc độ CPU tối đa:	4.1 GHz<br>  
Loại RAM:	DDR4 <br>
Dung lượng RAM:	8 GB  <br>
Tốc độ Bus RAM:	2666 MHz<br>
Loại ổ đĩa cứng:	SSD<br>
Dung lượng :	256 GB<br>
Bộ xử lý đồ họa:	NVIDIA GeForce GTX 1650<br>
Dung lượng card đồ họa:	4GB GDDR5<br>
Loại màn hình:	IPS-Level 45% NTSC, Thin Bezel<br>
Kích thước màn hình:	15.6 inch<br>
Độ phân giải màn hình:	1920 x 1080 Pixels<br>
Kết nối khác laptop:	Bluetooth v5<br>
HĐH kèm theo máy:	Windows 10 Home SL<br>
Loại Pin Laptop :	3 cell 51 Wh<br>
Khối lượng sản phẩm (kg):	1.9 kg<br>
Kích thước sản phẩm:	359 x 254 x 21.7 mm <br>
  
# Note: Only work in MAC OS Mojave 10.14.x 
  
How to create USB boot Mac:  
Step 1: Download and install clover in mac https://mackie100projects.altervista.org/download-clover-configurator/. 
Step 2: Download and unzip hackintosh-MSI-GF63 https://github.com/taigroddy/hackintosh-MSI-GF63. <br>
Step 2: Open app and go to Mount EFI. <br>
Step 3: Double click "Mount partition". <br>
Step 4: Next, copy EFI in hackintosh-MSI-GF63 to USB and done. <br>

# FIXED: 
AUDIO: <br>
- OPTION 1: First, remove AppleHDA.kext in ~/Library/Extentions. Then, download "Hackintosh Vietnam Tool 1.9.6" with link https://taimienphi.vn/download-hackintosh-vietnam-tool-for-mac-39155. Finally, install sound with VoodooHDA (in Kexts->Sound->VoodooHDA) and restart when it's done.   
- OPTION 2: You can download VoodooHDA.kext ver2.8.7 and add it to Systemt->Library->Extentions->Kexts (replace it if it's realy existed). 
Note: <br>
If the both options is not working, you should to use "Hackintosh Vietnam Tool 1.9.6" to repair it. The first, you need to remove the existing driver by installing all driver in Kexts->Sound, restart Clover and then reinstall only VoodooHDA with the option 1.<br>

Trackpad is jumping / lagging / skipping:  
- I don't know what is happen but the new version of VoodooI2C.kext (ver2.4.3) is the reason for this. So, you just need to use the old version - In my case, it is ver2.2.x). You can download the old version in https://github.com/VoodooI2C/VoodooI2C/releases and add it to EFI/Clover/kexts/Other (replace all). It's solved.  
