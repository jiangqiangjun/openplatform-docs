## 初始化

<style>
	table{
		border-collapse:collapse;
		width:100%;
	}
	table tr td{
		border:1px solid #000;
	}
</style>
<table >
<tr><td style="background-color:#ccc;text-align:center;width:80px;">定义</td><td colspan="2"><b>int Init(int nType = 0, byte []pParam = NULL);
</b></td><tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">函数库初始化(整个程序只需要调用一次)
</td></tr>
<tr><td rowspan="3" style="background-color:#ccc;text-align:center;">参数说明</td><td style="background-color:#ccc;text-align:center;width:20%;">名称</td><td style="background-color:#ccc;text-align:center">说明
</td></tr>
<tr style="text-align:center"><td>nType</td><td>保留</td></tr>
<tr style="text-align:center"><td>pParam</td><td>public int st_0_nAppType;//APP类型
<br>public int st_1_nSource;//来源
<br>public  int  st_2_language; //语言种类</td><tr>
<tr><td style="background-color:#ccc;text-align:center">返回</td><td colspan="2" style="text-align:center";>详见错误码说明
</td><tr>
</table>

## 反初始化

<table>
<tr><td style="background-color:#ccc;text-align:center;width:200px;">定义</td><td colspan="2"><b>void UnInit();</b></td><tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">函数库反初始化
</td></tr>
</table>

## 初始化服务（本地登入）

<table >
<tr><td style="background-color:#ccc;text-align:center;width:100px;">定义</td><td colspan="2">int SysInitLocal(String szDBFile);</td><tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">初始化服务，适用于本地登入</td></tr>
<tr><td rowspan="2" style="background-color:#ccc;text-align:center">参数说明</td><td style="background-color:#ccc;text-align:center;width:20%;">名称</td><td style="background-color:#ccc;text-align:center">说明
</td></tr>
<tr style="text-align:center"><td>szDBFile</td><td>本地设备信息数据存储文件的路径
</td></tr>
<tr><td style="background-color:#ccc;text-align:center">返回</td><td colspan="2" style="text-align:center";>详见错误码说明</td><tr>
</table>

## 初始化服务（AP模式）

<table >
<tr><td style="background-color:#ccc;text-align:center;width:100px;">定义</td><td colspan="2">int SysInitAsAPModle(String szDBFile);
</td></tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">初始化服务，适用于AP模式
</td></tr>
<tr><td rowspan="2" style="background-color:#ccc;text-align:center">参数说明</td><td style="background-color:#ccc;text-align:center;width:20%;">名称</td><td style="background-color:#ccc;text-align:center">说明
</td></tr>
<tr style="text-align:center"><td>szDBFile</td><td>AP模式设备信息存储的数据文件路径
</td></tr>
<tr><td style="background-color:#ccc;text-align:center">返回</td><td colspan="2" style="text-align:center";>详见错误码说明</td><tr>
</table>

## 初始化服务（云登录） 

<table >
<tr><td style="background-color:#ccc;text-align:center;width:100px;">定义</td><td colspan="2">int SysInitNet(String szIP, int nPort);
</td><tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">初始化服务，适用于云登入
</td></tr>
<tr><td rowspan="3" style="background-color:#ccc;text-align:center">参数说明</td><td style="background-color:#ccc;text-align:center;width:20%;">名称</td><td style="background-color:#ccc;text-align:center">说明
</td></tr>
<tr><td style="text-align:center">szIP</td><td style="text-align:center">服务器ip</td></tr>
<tr><td style="text-align:center">nPort</td><td style="text-align:center">端口号</td><tr>
<tr><td style="background-color:#ccc;text-align:center">返回</td><td colspan="2" style="text-align:center";>详见错误码说明
</td><tr>
</table>

## 初始化（NetSDK）

<table >
<tr><td style="background-color:#ccc;text-align:center;width:100px;">定义</td><td colspan="2">int InitNetSDK();</td><tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">初始化NetSDK</td></tr>
<tr><td rowspan="2" style="background-color:#ccc;text-align:center">参数说明</td><td style="background-color:#ccc;text-align:center;width:20%;">名称</td><td style="background-color:#ccc;text-align:center">说明
</td></tr>
<tr style="height:30px"><td></td><td></td></tr>
<tr><td style="background-color:#ccc;text-align:center">返回</td><td colspan="2" style="text-align:center";>详见错误码说明</td><tr>
</table>

## 反初始化（NetSDK）

<table>
<tr><td style="background-color:#ccc;text-align:center;width:100px;">定义</td><td colspan="2">void UnInitNetSDK();</td><tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">反初始化NetSDK</td></tr>
<tr><td rowspan="2" style="background-color:#ccc;text-align:center">参数说明</td><td style="background-color:#ccc;text-align:center;width:20%;">名称</td><td style="background-color:#ccc;text-align:center">说明
</td></tr>
<tr style="height:30px"><td></td><td></td></tr>
<tr><td style="background-color:#ccc;text-align:center">返回</td><td colspan="2" style="text-align:center";>详见错误码说明</td><tr>
</table>

## 初始化app证书

<table >
<tr><td style="background-color:#ccc;text-align:center;width:100px;">定义</td><td colspan="2">int XMCloundPlatformInit(String uuid, String appKey, String appSecret, int movedCard);</td><tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">初始化app证书，app运行调用一次即可
</td></tr>
<tr><td rowspan="5" style="background-color:#ccc;text-align:center">参数说明</td><td style="background-color:#ccc;text-align:center;width:20%;">名称</td><td style="background-color:#ccc;text-align:center">说明
</td></tr>
<tr style="text-align:center"><td>uuid</td><td>客户唯一标识</td></tr>
<tr style="text-align:center"><td>appKey</td><td>应用唯一标识符</td></tr>
<tr style="text-align:center"><td>appSecret</td><td>应用密钥</td></tr>
<tr style="text-align:center"><td>movedCard</td><td>移动取模基数</td></tr>
<tr><td style="background-color:#ccc;text-align:center">返回</td><td colspan="2" style="text-align:center";>0</td><tr>
</table>

## 初始化服务器ip和port

<table >
<tr><td style="background-color:#ccc;text-align:center;width:100px;">定义</td><td colspan="2">int SysSetServerIPPort(String szKey, String szServerIP, int nServerPort);
</td><tr>
<tr><td style="background-color:#ccc;text-align:center">描述</td><td colspan="2">如果帐户服务器IP不是默认，使用此接口进行配置
</td></tr>
<tr><td rowspan="4" style="background-color:#ccc;text-align:center">参数说明</td><td style="background-color:#ccc;text-align:center;width:20%;">名称</td><td style="background-color:#ccc;text-align:center">说明
</td></tr>
<tr><td style="text-align:center">szKey</td><td style="text-align:center">帐户服务id，通用账号服务szKey:"MI_SERVER"</td></tr>
<tr><td style="text-align:center">szServerIP</td><td style="text-align:center">服务器ip</td></tr>
<tr><td style="text-align:center">nServerPort</td><td style="text-align:center">端口号</td><tr>
<tr><td style="background-color:#ccc;text-align:center">返回</td><td colspan="2" style="text-align:center";>0
</td><tr>
</table>
