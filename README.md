3、部署workers脚本：
Wordkers脚本：【(https://github.com/3Kmfi6HP/EDtunnel/blob/main/_worker.js)】

部署中修改两个地方：替换UUID，CF反代IP，反代IP可以使用下面大佬提供的.

http = [80, 8080, 8880, 2052, 2086, 2095, 2082]

https = [443, 8443, 2053, 2096, 2087, 2083]

查询的路由哥CF反代IP 域名

cdnhk.huabuxiang.vip

ali.055500.xyz

yx.kkkong.pp.ua

cdn.shanggan.pp.ua

443.xiangmq1969.xyz

hk.100366.xyz

sp.rweek.top

CF 官方IP 域名

cip.951535.xyz

大佬提供的CF反代IP：

cdn-all.xn--b6gac.eu.org cdn.xn--b6gac.eu.org cdn-b100.xn--b6gac.eu.org edgetunnel.anycast.eu.org cdn.anycast.eu.org

优选域名：

icook.hk ip.sb japan.com skk.moe www.visa.com www.visa.co.jp www.visakorea.com www.gco.gov.qa www.csgo.com www.whatismyip.com gamer.com.tw steamdb.info toy-people.com silkbook.com cdn.anycast.eu.org icook.hk shopify.com www.visa.com.tw time.is japan.com www.hugedomains.com www.visa.com.sg www.whoer.net www.visa.com.hk malaysia.com www.visa.co.jp www.ipget.net icook.tw www.visa.com www.gov.ua www.udacity.com www.shopify.com www.whatismyip.com singapore.com www.visakorea.com www.csgo.com russia.com ip.sb www.4chan.org www.glassdoor.com xn--b6gac.eu.org www.digitalocean.com www.udemy.com cdn-all.xn--b6gac.eu.org dnschecker.org tasteatlas.com pixiv.net comicabc.com icook.tw gamer.com.tw steamdb.info toy-people.com silkbook.com

4、套Tls设置v2rayN（建议套上Tls）需要域名
套Tls需要将域名托管到Cloudflare，所以配置之前要想将域名托管设置好

4.1、添加自定义域

4.2、获取vless订阅地址

4.3、v2rayN中添加vless订阅地址

4.4、修改端口为443，传输层安全（Tls）开启
