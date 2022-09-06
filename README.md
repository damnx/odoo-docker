1 xoá file etc/odoo/odoo.conf

2 đổi tên file odoo.conf.dev thành odoo.conf




3 build docker

docker-compose up -d 


4 thêm 
dòng file etc/odoo/odoo.conf : addons_path = /usr/lib/python3/dist-packages/odoo/addons,/mnt/extra-addons

khi build xong dòng addons_path đã có addons_path = /usr/lib/python3/dist-packages/odoo/addons chỉ cần thêm ,/mnt/extra-addons
