# man 手册查看约定(IOS 命令参考约定)

```
NAME
       ip - show / manipulate routing, devices, policy routing and tunnels

SYNOPSIS

       ip [ OPTIONS ] OBJECT { COMMAND | help }

       ip [ -force ] -batch filename

       OBJECT := { link | address | addrlabel | route | rule | neigh | ntable | tunnel | tuntap | maddress | mroute | mrule | monitor | xfrm | netns | l2tp
               | tcp_metrics | token | macsec }

       OPTIONS := { -V[ersion] | -h[uman-readable] | -s[tatistics] | -d[etails] | -r[esolve] | -iec | -f[amily] { inet | inet6 | ipx | dnet | link } | -4 |
               -6 | -I | -D | -B | -0 | -l[oops] { maximum-addr-flush-attempts } | -o[neline] | -rc[vbuf] [size] | -t[imestamp] | -ts[hort] | -n[etns] name
               | -a[ll] | -c[olor] }
```

如上所是

```
$ man ip
```
截取的一部分，大概懂但是看不太懂？来看下 IOS 命令参考约定就懂了         
IOS 命令参考约定：       
**1、互斥元素用竖线(|)隔开**    
**2、中括号 [] 表示可选项**    
**3、大括号 {} 表示必选项**      
**4、中括号内的大括号 [{}] 表示可选项中的必选项**
