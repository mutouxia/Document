# 可选项参数

#### 订阅

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| lv | Int | 否 | 1～3（bronze / silver / gold（ | - | ✕ | ✕ |

#### 托管

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| mitm | Int | 否 | 1 | Surge 3 Pro | ✓ | ✕ |
| media | Int | 否 | 1 | Surge 3 Pro | ✕ | ✕ |
| class | String | 否 | bronze / silver / gold | - | ✓ | ✕ |
| noclass | String | 否 | bronze / silver / gold | - | ✓ | ✕ |
| area | String | 否 | 节点的国家英文缩写（eg:hk） | - | ✓ | ✕ |
| isp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | - | ✓ | ✕ |
| noisp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | - | ✓ | ✕ |

#### List

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| list | Int | 是 | 1 | Surge 3 Pro | ✓ | ✕ |
| type | String | 否 | all / auto / media / relay / back / gamer | Surge 3 Pro | ✓ | ✕ |
| class | String | 否 | bronze / silver / gold | Surge 3 Pro | ✓ | ✕ |
| noclass | String | 否 | bronze / silver / gold | Surge 3 Pro | ✓ | ✕ |
| area | String | 否 | 节点的国家英文缩写（eg:hk） | Surge 3 Pro | ✓ | ✕ |
| noarea | String | 否 | 节点的国家英文缩写（eg:hk） | Surge 3 Pro | ✓ | ✕ |
| isp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | Surge 3 Pro | ✓ | ✕ |
| noisp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | Surge 3 Pro | ✓ | ✕ |



使用方法：将参数添加到托管/订阅地址尾部

`https://dler.cloud/link/token?surge=3` `&mitm=1` `&class=gold`

