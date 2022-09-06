1 xoá file etc/odoo/odoo.conf

2 đổi tên file odoo.conf.dev thành odoo.conf

3 thêm 
dòng : addons_path = /usr/lib/python3/dist-packages/odoo/addons,/mnt/extra-addons

khi build xong dòng addons_path đã có addons_path = /usr/lib/python3/dist-packages/odoo/addons chỉ cần thêm ,/mnt/extra-addons


build docker

docker-compose up -d 
