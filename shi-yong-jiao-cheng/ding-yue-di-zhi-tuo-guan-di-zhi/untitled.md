# 可选项参数

#### 订阅

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| is\_mu | Int | 否 | 1（公共端口） | - | ✓ | ✕ |
| mu | String | 是 | ss / ssr | - | ✕ | ✕ |

#### 托管

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| mitm | Int | 否 | 1（MitM 证书） | Surge Pro | ✓ | ✕ |
| type | String | 否 | media / relay / back / gamer | - | ✓ | ✕ |
| lv | Int | 否 | 1～5 | - | ✓ | ✕ |
| nolv | Int | 否 | 1～5 | - | ✓ | ✕ |
| area | String | 否 | 节点的国家英文缩写（eg:hk） | - | ✓ | ✓ |
| noarea | String | 否 | 节点的国家英文缩写（eg:hk） |  |  |  |
| isp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | - | ✓ | ✕ |
| noisp | String | 否 | 节点的网络运营商或后缀名（空格请用"%20"代替） | - | ✓ | ✕ |
| source | URL | 否 | 自定义规则 | - | ✓ | ✕ |
| custom | URL | 否 | 在当前托管规则前面加入自定义规则 | - | ✓ | ✕ |
| dns | Int | 否 | 为当前规则加入自定义DNS | Clash | ✓ | ✕ |
| tap | Int | 否 | TAP模式 | Clash | ✓ | ✕ |
| ssid | Int | 否 | 在使用特定的Wi-Fi 时关闭Surge | Surge | ✓ | ✕ |

#### List

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#x53C2;&#x6570;</th>
      <th style="text-align:left">&#x7C7B;&#x578B;</th>
      <th style="text-align:left">&#x5FC5;&#x987B;</th>
      <th style="text-align:left">&#x53D8;&#x91CF;&#x6216;&#x63CF;&#x8FF0;</th>
      <th style="text-align:left">&#x517C;&#x5BB9;</th>
      <th style="text-align:left">&#x591A;&#x91CD;&#x6761;&#x4EF6;</th>
      <th style="text-align:left">&#x590D;&#x7528;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">list</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x662F;</td>
      <td style="text-align:left">1</td>
      <td style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
      </td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">type</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">all / auto / media / relay / back / gamer</td>
      <td style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
      </td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">lv</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">1&#xFF5E;5</td>
      <td style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
      </td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">nolv</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">1&#xFF5E;5</td>
      <td style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
      </td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">area</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x8282;&#x70B9;&#x7684;&#x56FD;&#x5BB6;&#x82F1;&#x6587;&#x7F29;&#x5199;&#xFF08;eg:hk&#xFF09;</td>
      <td
      style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
        </td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2713;</td>
    </tr>
    <tr>
      <td style="text-align:left">noarea</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x8282;&#x70B9;&#x7684;&#x56FD;&#x5BB6;&#x82F1;&#x6587;&#x7F29;&#x5199;&#xFF08;eg:hk&#xFF09;</td>
      <td
      style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
        </td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2713;</td>
    </tr>
    <tr>
      <td style="text-align:left">isp</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x8282;&#x70B9;&#x7684;&#x7F51;&#x7EDC;&#x8FD0;&#x8425;&#x5546;&#x6216;&#x540E;&#x7F00;&#x540D;&#xFF08;&#x7A7A;&#x683C;&#x8BF7;&#x7528;&quot;%20&quot;&#x4EE3;&#x66FF;&#xFF09;</td>
      <td
      style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
        </td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">noisp</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x8282;&#x70B9;&#x7684;&#x7F51;&#x7EDC;&#x8FD0;&#x8425;&#x5546;&#x6216;&#x540E;&#x7F00;&#x540D;&#xFF08;&#x7A7A;&#x683C;&#x8BF7;&#x7528;&quot;%20&quot;&#x4EE3;&#x66FF;&#xFF09;</td>
      <td
      style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
        </td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2715;</td>
    </tr>
  </tbody>
</table>多重条件：多个可选项参数搭配使用

复用：某些可选项参数可以使用多个变量值（`&area=hk+jp`）



使用方法：将参数添加到托管/订阅地址尾部

`https://dler.cloud/subscrile/token?surge=3&mitm=1&lv=3`

