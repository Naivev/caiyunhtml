因为彩云API免费版只支持未来48H的数据，所以实况天气和小时级预报使用彩云API，未来7天预报和灾害预警信息使用和风API。

为什么不都用和风API：因为个人本地实测彩云数据更准一点。

106-108行换成自己的api密钥和经纬度。

例如：

const LOCATION = '改成自己的';（经纬度）

const CAIYUN = '改成自己的'; （彩云api密钥）

const HEFENG = '改成自己的';（和风api密钥）


换成：

const LOCATION = '116.405419,39.924232';

const CAIYUN = 'abcdefg';

const HEFENG = 'abcdefg';



彩云API申请：https://docs.caiyunapp.com/weather-api/index.html 免费1w次/天

和风API申请：https://dev.qweather.com 免费1k次/天

经纬度获取：https://api.map.baidu.com/lbsapi/getpoint/index.html

本地html，直接保存到本地用记事本改完api密钥和经纬度用浏览器打开就行。

![image](https://github.com/user-attachments/assets/60f5549e-8ac0-4b8e-b361-e8da05309819)
