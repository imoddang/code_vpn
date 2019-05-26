Script Installation

OpenVPN, Pritunl, Proxy, SHH Dropbear, Web Panel

วิธีติดตั้ง openvpn
รันคำสั่งตามนี้

wget https://raw.githubusercontent.com/imoddang/code_vpn/master/Install && chmod +x Install && bash Install

*******************

สคริปแก้ไขให้ใช้ user root ได้
สำหรับ debian9

wget -O /etc/ssh/sshd_config 'https://raw.githubusercontent.com/imoddang/code_vpn/master/sshd_config'

เสร็จแล้ว กำหนด รหัสผ่าน root
passwd root 
ใส่รหัส

เสร็จแล้ว reboot
