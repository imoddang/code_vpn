Script Installation

OpenVPN, Pritunl, Proxy, SHH Dropbear, Web Panel

วิธีติดตั้ง openvpn
รันคำสั่งตามนี้

wget https://raw.githubusercontent.com/imoddang/code_vpn/master/Install && chmod +x Install && bash Install

*******************

สคริปแก้ไขให้ใช้ user root ได้
สำหรับ debian 8,9
รันคำสั่งตามนี้

wget -O /etc/ssh/sshd_config 'https://raw.githubusercontent.com/imoddang/code_vpn/master/sshd_config'

เสร็จแล้ว กำหนด รหัสผ่าน root
พิมพ์ passwd root กด enter
ใส่รหัส แล้วแต่มึงใส่ แล้วกด enter
เสร็จแล้ว พิมพ์ reboot แล้วกด enter
