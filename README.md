# hackintosh-MSI-GF63 

Model: https://www.msi.com/Laptop/support/GF63-THIN-9SC.
Motherboard: Intel chipset HM370
Nhà sản xuất:	MSI
CPU:	Intel Core i5
Loại CPU:	9300H
Tốc độ CPU:	2.40 GHz
Bộ nhớ đệm:	8MB cache
Tốc độ CPU tối đa:	4.1 GHz
Loại RAM:	DDR4
Dung lượng RAM:	8 GB
Tốc độ Bus RAM:	2666 MHz
Loại ổ đĩa cứng:	SSD
Dung lượng :	256 GB
Bộ xử lý đồ họa:	NVIDIA GeForce GTX 1650
Dung lượng card đồ họa:	4GB GDDR5
Loại màn hình:	IPS-Level 45% NTSC, Thin Bezel
Kích thước màn hình:	15.6 inch
Độ phân giải màn hình:	1920 x 1080 Pixels
Kết nối khác laptop:	Bluetooth v5
HĐH kèm theo máy:	Windows 10 Home SL
Loại Pin Laptop :	3 cell 51 Wh
Khối lượng sản phẩm (kg):	1.9 kg
Kích thước sản phẩm:	359 x 254 x 21.7 mm
  
# Note: Only work in MAC OS Mojave 10.14.x 
  
How to create USB boot Mac:  
Step 1: Download and install clover in mac https://mackie100projects.altervista.org/download-clover-configurator/. 
Step 2: Download and unzip hackintosh-MSI-GF63 https://github.com/taigroddy/hackintosh-MSI-GF63. <br>
Step 2: Open app and go to Mount EFI. <br>
Step 3: Double click "Mount partition". <br>
Step 4: Next, copy EFI in hackintosh-MSI-GF63 to USB and done. <br>

# FIXED: 
AUDIO: First, remove AppleHDA.kext in ~/Library/Extentions. Then, download "Hackintosh Vietnam Tool 1.9.6" with link https://taimienphi.vn/download-hackintosh-vietnam-tool-for-mac-39155. Finally, install sound with VoodooHDA (in Kexts->Sound->VoodooHDA) and restart when it's done.   

