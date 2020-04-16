# 可选项参数

#### 订阅

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| mu | String | 是 | ss / ss\_public / ssr / gamer | - | ✕ | ✕ |

#### 托管

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 | 简单正则 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| type | String | 否 | media / relay / back / gamer / love | - | ✓ | ✕ | ✕ |
| lv | Int | 否 | 1～5 | - | ✓ | ✕ | ✕ |
| nolv | Int | 否 | 1～5 | - | ✓ | ✕ | ✕ |
| area | String | 否 | 节点的国家英文缩写（eg:hk） | - | ✓ | ✓ | ✕ |
| noarea | String | 否 | 节点的国家英文缩写（eg:hk） | - | ✓ | ✓ | ✕ |
| match | String | 否 | 节点关键词匹配（可使用"\|"筛选多个节点） | - | ✓ | ✕ | ✓ |
| nomatch | String | 否 | 节点关键词匹配（可使用"\|"筛选多个节点） | - | ✓ | ✕ | ✓ |
| head | URL | 否 | 自定义托管规则头部 | - | ✓ | ✕ | ✕ |
| custom | URL | 否 | 在当前托管规则前面加入自定义规则 | - | ✓ | ✕ | ✕ |
| source | URL | 否 | 自定义托管规则 | - | ✓ | ✕ | ✕ |
| dns | Int | 否 | 为当前规则加入自定义DNS | Clash | ✓ | ✕ | ✕ |
| tap | Int | 否 | TAP模式 | Clash | ✓ | ✕ | ✕ |
| ssid | String | 否 | 在使用特定的Wi-Fi 时将Surge 暂时挂起 | Surge | ✓ | ✕ | ✕ |
| emoji | Int | 否 | 0（默认开启） | - | ✓ | ✕ | ✕ |

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
      <th style="text-align:left">&#x7B80;&#x5355;&#x6B63;&#x5219;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">list</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x662F;</td>
      <td style="text-align:left">surge / quantumultx / clash</td>
      <td style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
      </td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
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
        <td style="text-align:left">&#x2715;</td>
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
        <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">match</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x8282;&#x70B9;&#x5173;&#x952E;&#x8BCD;&#x5339;&#x914D;&#xFF08;&#x53EF;&#x4F7F;&#x7528;&quot;|&quot;&#x7B5B;&#x9009;&#x591A;&#x4E2A;&#x8282;&#x70B9;&#xFF09;</td>
      <td
      style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
        </td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2715;</td>
        <td style="text-align:left">&#x2713;</td>
    </tr>
    <tr>
      <td style="text-align:left">nomatch</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x8282;&#x70B9;&#x5173;&#x952E;&#x8BCD;&#x5339;&#x914D;&#xFF08;&#x53EF;&#x4F7F;&#x7528;&quot;|&quot;&#x7B5B;&#x9009;&#x591A;&#x4E2A;&#x8282;&#x70B9;&#xFF09;</td>
      <td
      style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
        </td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2715;</td>
        <td style="text-align:left">&#x2713;</td>
    </tr>
    <tr>
      <td style="text-align:left">emoji</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">0&#xFF08;&#x9ED8;&#x8BA4;&#x5F00;&#x542F;&#xFF09;</td>
      <td style="text-align:left">
        <p>Surge Pro</p>
        <p>QuantumultX</p>
        <p>Clash</p>
      </td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
  </tbody>
</table>多重条件：多个可选项参数搭配使用

复用：某些可选项参数可以使用多个变量值（`&area=hk+jp`）

简单正则：某些可选项参数可以使用简单正则（`&match=香港|澳门|台湾`）



使用方法：将可选项参数添加到托管/订阅地址尾部

`https://dler.cloud/subscrile/token?surge=3&mitm=1&lv=3`

