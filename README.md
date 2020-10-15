# Hyper-V-install-note
Install Hyper-V for using Windows10 and visual studio

0. Download hype-v vm(win10 and visual studio)

 中文

  https://developer.microsoft.com/zh-tw/windows/downloads/virtual-machines/
 
 英文
 
  https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/
  
 license 
  
  https://windowsdev.azureedge.net/eulas/WindowsDeveloperVirtualMachineEula20151118.pdf

1. enable VM in BIOS : 
 - lenovo ex: reboot > F1 to enter BIOS > enable VM > save and restart
 - ref : https://techcommunity.microsoft.com/t5/itops-talk-blog/step-by-step-enabling-hyper-v-for-use-on-windows-10/ba-p/267945 

2. Install Hyper-V on Windows 10
 - 開始 > 搜尋 : 控制台 > 控制台\所有控制台項目\程式和功能 > 開啟或關閉windows功能 > checked Hyper-V
 - ref : https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v
 
3. Create a Virtual Machine with Hyper-V
 - 開始 > Hyper-v管理員 > right click on TPEA90095984 > 匯入虛擬機器 > 尋找資料夾 > 瀏覽 : select downloaded hype-V VM folder>
 下一步... fin > right click on 匯入的虛擬機 > 設定 : 記憶體(建議8G up); 處理器(建議2up) 
 > right click on 匯入的虛擬機 > 連線
 - ref : https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/quick-create-virtual-machine
