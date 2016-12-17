### cmd_hosts
> a tool for changing hosts file
NAME
		cbind -- change the enviorenment hosts bind.
SYNOPSIS
		cbind [-adn]
USAGE
		cbind [pre | daily | beta ...]
			eg: cbind pre

		-a add bind to hosts file.
			eg: cbind -a 12.34.56.78 abc.efg.com

		-d delete bind from hosts file.
			eg: cbind -d [pre | daily | beta ...] 1.2.3.4
					cbind -d [pre | daily | beta ...] taobao.com
					cbind -d [pre | daily | beta ...] tencent.com baidu.com
					cbind -d [pre | daily | beta ...] * (delete all hosts from hosts file except localhost)
		-n annotate bind from hosts file.
			eg: cbind -n [pre | daily | beta ...] 1.2.3.4
					cbind -n [pre | daily | beta ...] taobao.com
					cbind -n [pre | daily | beta ...] tencent.com baidu.com
					cbind -n [pre | daily | beta ...] * (annotate all hosts from hosts file except localhost)
