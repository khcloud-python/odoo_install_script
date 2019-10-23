这是根据 

https://raw.githubusercontent.com/Yenthe666/InstallScript/XX.0/odoo_install.sh

修改的odoo安装脚本。主要修改点如下：

1、Ubuntu源换成阿里云的源，便于中国用户安装

2、根据Odoo官方的安装脚本，增加 rtlcss 组件

3、根据Odoo官方的安装脚本，wkhtmltox、postgresql、node_8.x等组件都安装与Ubuntu版本相应的版本

4、增加 xlwt、pycryptodome Python模块

