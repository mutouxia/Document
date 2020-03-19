# 可选项参数

#### 订阅

| 参数 | 类型 | 必须 | 变量或描述 | 兼容 | 多重条件 | 复用 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| mu | String | 是 | ss / ssr / gamer | - | ✕ | ✕ |

#### 托管

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
      <td style="text-align:left">mitm</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">1&#xFF08;MitM &#x8BC1;&#x4E66;&#xFF09;</td>
      <td style="text-align:left">
        <p>Surge</p>
        <p>QuantumultX</p>
      </td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">type</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">media / relay / back / gamer / love</td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">lv</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">1&#xFF5E;5</td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">nolv</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">1&#xFF5E;5</td>
      <td style="text-align:left">-</td>
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
      style="text-align:left">-</td>
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
      style="text-align:left">-</td>
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
      style="text-align:left">-</td>
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
      style="text-align:left">-</td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2715;</td>
        <td style="text-align:left">&#x2713;</td>
    </tr>
    <tr>
      <td style="text-align:left">head_custom</td>
      <td style="text-align:left">URL</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x81EA;&#x5B9A;&#x4E49;&#x6258;&#x7BA1;&#x89C4;&#x5219;&#x5934;&#x90E8;</td>
      <td
      style="text-align:left">-</td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2715;</td>
        <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">rule_custom</td>
      <td style="text-align:left">URL</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x5728;&#x5F53;&#x524D;&#x6258;&#x7BA1;&#x89C4;&#x5219;&#x524D;&#x9762;&#x52A0;&#x5165;&#x81EA;&#x5B9A;&#x4E49;&#x89C4;&#x5219;</td>
      <td
      style="text-align:left">-</td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2715;</td>
        <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">rule_source</td>
      <td style="text-align:left">URL</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x81EA;&#x5B9A;&#x4E49;&#x6258;&#x7BA1;&#x89C4;&#x5219;</td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">dns</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x4E3A;&#x5F53;&#x524D;&#x89C4;&#x5219;&#x52A0;&#x5165;&#x81EA;&#x5B9A;&#x4E49;DNS</td>
      <td
      style="text-align:left">Clash</td>
        <td style="text-align:left">&#x2713;</td>
        <td style="text-align:left">&#x2715;</td>
        <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">tap</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">TAP&#x6A21;&#x5F0F;</td>
      <td style="text-align:left">Clash</td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">ssid</td>
      <td style="text-align:left">String</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">&#x5728;&#x4F7F;&#x7528;&#x7279;&#x5B9A;&#x7684;Wi-Fi &#x65F6;&#x5C06;Surge
        &#x6682;&#x65F6;&#x6302;&#x8D77;</td>
      <td style="text-align:left">Surge</td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
    <tr>
      <td style="text-align:left">emoji</td>
      <td style="text-align:left">Int</td>
      <td style="text-align:left">&#x5426;</td>
      <td style="text-align:left">0&#xFF08;&#x9ED8;&#x8BA4;&#x5F00;&#x542F;&#xFF09;</td>
      <td style="text-align:left">-</td>
      <td style="text-align:left">&#x2713;</td>
      <td style="text-align:left">&#x2715;</td>
      <td style="text-align:left">&#x2715;</td>
    </tr>
  </tbody>
</table>#### List

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
      <td style="text-align:left">1</td>
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

