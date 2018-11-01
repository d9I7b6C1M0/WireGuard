centOS7+ WireGuard一鍵安裝脚本:

1)  wireguard_centos7_install.sh

2)  chmod +x wireguard_centos7_install.sh

3)  ./wireguard_centos7_install.sh

4)  安装完成后，服务就自动启动了，可以通过命令 wg 检查启动是否成功，成功的话会输出如下内容：

     interface: wg0
     
     public key: xxxxxxxxxx
     
     private key: (hidden)
     
     listening port: xxxxx
     
     peer: xxxxxxxxxxxxxxxxx
     
     allowed ips: 10.0.0.2/xx
     
5)  然后 vi /etc/wireguard/client.conf

    把client.conf的内容复制到记事本，另存xxx.conf文件,将此配置文件导入客户端即可
