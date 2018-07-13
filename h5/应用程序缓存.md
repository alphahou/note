### 缓存

1. 通过创建cache manifest，可以创建web 应用的离线版本

2. 优势：

   * 可配置需要缓存的资源
   * 网络无连接应用仍可用
   * 本地读取缓存资源，提升访问速度
   * 减少请求，缓解服务器压力

3. cache manifest基础：

   `<html lang="en" manifest="demo.appcache">`

   ```
   //in demo.appcache
   CACHE MANIFEST
   //需要缓存的文件清单列表
   
   CACHE:
   ../images/1.jpg  //缓存图片1,2
   ../images/2.jpg
   * //代表所有文件
   
   
   //配置每一次都需要重新从服务器获取的文件清单列表
   NETWORK:
   ../images/3.jpg  //不缓存图片3
   
   
   //配置如果文件无法获取则使用指定的文件进行替代
   FALLBACK:
   ../images/4.jpg ../images/banner_1.jpg //如果找不到图片4，用banner_1 代替
   / ../images/banner_1.jpg //任何找不到的文件都使用banner_1代替
   
   ```

   

   

   