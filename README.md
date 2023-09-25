# unicom
联通抓token_online

看的懂的可以自己看https://chinatelecomoperators.notion.site/chinatelecomoperators/ChinaUnicom-5959008dfc2a477baf90471682f770fd

看不懂的看我接下来的步骤：
拉取两个文件：
①：【ql raw https://github.com/ChinaTelecomOperators/ChinaUnicom/releases/download/Prerelease-Alpha/10010_send_sms.js;】

②：【ql raw https://github.com/ChinaTelecomOperators/ChinaUnicom/releases/download/Prerelease-Alpha/10010_sms_sign.js;】

其他的我们用不上，可以不拉取

设置环境变量：
名称：【ChinaUnicom_10010v4_mobile】  值：1XXXXXXXXX(手机号)    【这一步填写完后，运行上面第一个文件，会发送一个验证码到你手机号，验证码输入到下面的这个值里】

名称：【ChinaUnicom_10010v4_code】  值：（这里填的是上面运行后收到的短信验证码）  【然后运行上面的第二个文件】

运行完后，查看第二个文件的日志，里面往下翻就能找到我们需要的token_online

![Uploading 1695646229855(1).jpg…]()
