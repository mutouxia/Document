# 可选项参数

#### 订阅

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| is\_mu | Int | 否 | 1（公共端口） | - | ✓ | ✕ |
| lv | Int | 否 | 1～3（bronze / silver / gold） | - | ✕ | ✕ |

#### 托管

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| is\_mu | Int | 否 | 1（公共端口） | - | ✓ |  |
| mitm | Int | 否 | 1（MitM 证书） | Surge 3 Pro | ✓ | ✕ |
| type | String | 否 | media / relay / back | - | ✓ | ✕ |
| media | Int | 否 | 1（流媒体规则） | Surge 3 Pro | ✕ | ✕ |
| class | String | 否 | bronze / silver / gold | - | ✓ | ✕ |
| noclass | String | 否 | bronze / silver / gold | - | ✓ | ✕ |
| area | String | 否 | 节点的国家英文缩写（eg:hk） | - | ✓ | ✓ |
| isp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | - | ✓ | ✕ |
| noisp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | - | ✓ | ✕ |
| source | URL | 否 | 自定义规则 | - | ✓ | ✕ |
| custom | URL | 否 | 在当前托管规则前面加入自定义规则 | - | ✓ | ✕ |

#### List

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| list | Int | 是 | 1 | Surge 3 Pro | ✓ | ✕ |
| type | String | 否 | all / auto / media / relay / back | Surge 3 Pro | ✓ | ✕ |
| class | String | 否 | bronze / silver / gold | Surge 3 Pro | ✓ | ✕ |
| noclass | String | 否 | bronze / silver / gold | Surge 3 Pro | ✓ | ✕ |
| area | String | 否 | 节点的国家英文缩写（eg:hk） | Surge 3 Pro | ✓ | ✓ |
| noarea | String | 否 | 节点的国家英文缩写（eg:hk） | Surge 3 Pro | ✓ | ✕ |
| isp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | Surge 3 Pro | ✓ | ✕ |
| noisp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | Surge 3 Pro | ✓ | ✕ |

多重条件：多个可选项参数搭配使用

复用：某个可选项参数可以使用多个变量值（`&area=hk+jp`）



使用方法：将参数添加到托管/订阅地址尾部

`https://dler.cloud/link/token?surge=3` `&mitm=1` `&class=gold`

