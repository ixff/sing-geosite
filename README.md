## 本仓库不再维护，请使用 [ixff/meta-rules-dat](https://github.com/ixff/meta-rules-dat)

## 说明

1. 本仓库目的在于让PT站点tracker服务器域名直连而不走代理。
2. 相比原仓库的变化：
   
   数据源由 [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) --> [ixff/v2ray-rules-dat](https://github.com/ixff/v2ray-rules-dat)，其唯一改变是完善了[category-pt](https://github.com/ixff/domain-list-community/blob/master/data/category-pt)。
3. 使用方法：
   
   `geosite.db`下载地址：[GitHub Releases](https://github.com/ixff/sing-geosite/releases/latest/download/geosite.db) 或者 [jsdelivr](https://cdn.jsdelivr.net/gh/ixff/sing-geosite@release/geosite.db)

   添加规则让全部PT站点域名都走直连：
   ```
   geosite:category-pt
   ```
   （注：可能会有“漏网之鱼”，原因见2中数据源仓库category-pt文件顶部的说明。）
   
   规则语法请参考所使用的软件，更多使用情形请参考2中的说明。
4. 如果你发现缺少某些站点域名或其tracker域名，请[到 ixff/domain-list-community 仓库提issue](https://github.com/ixff/domain-list-community/issues/new?assignees=&labels=&projects=&template=%E5%9F%9F%E5%90%8D%E6%9B%B4%E6%96%B0.md&title=%E3%80%90%E5%9F%9F%E5%90%8D%E6%9B%B4%E6%96%B0%E3%80%91XXX)，维护该列表需要大家的共同努力。


# Domain list community

This project manages a list of domains, to be used as geosites for routing purpose in [SagerNet/sing-box](https://github.com/SagerNet/sing-box).

Based on [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat)

You could download the lastest `geosite.db` from [https://github.com/soffchen/sing-geosite/releases/latest/download/geosite.db](https://github.com/soffchen/sing-geosite/releases/latest/download/geosite.db) or [https://cdn.jsdelivr.net/gh/soffchen/sing-geosite@release/geosite.db](https://cdn.jsdelivr.net/gh/soffchen/sing-geosite@release/geosite.db) with CDN powered by jsdelivr.
