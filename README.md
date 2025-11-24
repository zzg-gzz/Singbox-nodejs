### 更新说明：适用128M内存以上环境，不建议freecloudpanel使用（64M内存）

* 精简化：去除哪吒、argo隧道；保留3种协议：tuic、hy2、vless+xtls+reality

* uuid自动生成
  
* 自动重启：每天凌晨00:03自动执行一次Sing-box重启，清除缓存
  
* TCP/UDP端口可共用
  
### 使用说明：

1：start.sh+index.js+package.json上传至服务器

2：Start.sh文件中输入tuic/hy2/vless端口，保存。TCP、UDP端口可共用，但tuic/hy2都是UDP，不能用同一端口，没有端口则留空，不启用该协议节点。

3：开机
