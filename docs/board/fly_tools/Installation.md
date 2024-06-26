## 安装FLY-Tools

1. 拉取最新版本Klipper

   ```
   cd ~/klipper
   git pull
   ```

   - 如果您修改过本地klipper源码导致拉取失败，请使用以下命令。 （此操作将丢弃您之前修改过的文件）

   ```
   cd ~/klipper
   git checkout .
   git pull
   ```

2. 拉取最新的Katapult(原Canboot)

   ```
   cd ~/
   git clone https://github.com/Arksine/katapult
   ```

3. - 安装Fly-Tools服务

     * 安装过程依赖于Git服务商。如果遇到下载进度卡住不动，请按 `CTRL+C` 退出重试

     * Github每小时最大请求次数60次，Gitee未知
   
     - 国内用户建议通过Gitee获取安装脚本

       ```
       curl -kfsSL https://gitee.com/zxkxz/FLY-Tools/raw/main/scripts/install.sh | sudo bash
       ```

       

     - 通过Github获取安装脚本

       ```
       curl -kfsSL https://raw.githubusercontent.com/kluoyun/FLY-Tools/main/scripts/install.sh | sudo bash
       ```
   
   
   
   <!-- tabs:start -->
   
   ### ****FLY-Gemini**,**FLY-π**,**FLY-C8**,**FLY-PI-v2**的安装选项**
   
   ![tools](../../images/boards/fly_tools/flyh5.png)
   
   ### ****FLY-lite2**的安装选项**
   
   ![tools](../../images/boards/fly_tools/flyh3.png)
   

<!-- tabs:end -->

1. 打开浏览器
   - 默认端口9999
   - `http://{你的设备IP}:9999/`