1.在/root目录解压openvpn.template.tgz
2./run 可以生成一个用户的配置及服务的配置, 用户test_user的配置在,
openvpn/easy-rsa/user/下
3. 启动vpn: cd openvpn;./openvpn start
4. 停止vpn: cd openvpn;./openvpn stop
5. 增加用户: cd openvpn/easy-rsa;./addvpnuser xxxxx 
   能在/root/openvpn/easy-rsa/user目录下生成该用户的配置。

