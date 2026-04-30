 * Cloudflare Worker: Vless
 * 1. 推荐workers部署。
 * 2. 千兆带宽专用，专为大流量、高负载、巨型吞吐量设计。
 * 3. 无订阅、纯手搓。
 * 4. 客户端path写法,支持txt格式，例如：/?ip=dsl253-007-079.nyc1.dsl.speakeasy.net  ; /?ip=https://raw.githubusercontent.com/hofccyf/myip/refs/heads/main/us.txt  ; /?ip=66.253.7.79 建议更改成你自己的。
 * 注意:如果节点不通.需在设置-运行时-兼容日期-修改为2026年2月24日之前
 * 完整节点示例  vless://88888888-8888-8888-8888-888888888888@goodluck.zone.id:443?path=%2F%3Fip%3Dusip.vpndns.net&security=tls&encryption=none&insecure=1&host=666.ccav.eu.cc&fp=random&type=ws&allowInsecure=1&sni=666.ccav.eu.cc#%E4%B8%89%E7%BD%91%E4%BC%98%E9%80%89
