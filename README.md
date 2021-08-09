# vue-basic-tool

> 基于vue写的常用验证

## Installing

```
npm i vue-basic-tool
```

## Usage
```
import tools from 'vue-basic-tool'

Vue.use(tools)
```

## methods
  <table>
    <tr>
      <td colspan="4">isEmail()  &nbsp;&nbsp;&nbsp;&nbsp;验证邮箱</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>邮箱</td>
      <td>String</td>
      <td>this.$tools.isEmail('test@163.com')</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isMobile()  &nbsp;&nbsp;&nbsp;&nbsp;验证手机号</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>手机号</td>
      <td>String</td>
      <td>this.$tools.isMobile('12345678901')</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isPhone()  &nbsp;&nbsp;&nbsp;&nbsp;验证电话号</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>电话号</td>
      <td>String</td>
      <td>this.$tools.isPhone('010-66666666')</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isURL()  &nbsp;&nbsp;&nbsp;&nbsp;验证url地址</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>地址</td>
      <td>String</td>
      <td>this.$tools.isURL('http://www.baidu.com')</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isString()  &nbsp;&nbsp;&nbsp;&nbsp;是否字符串</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>字符串</td>
      <td>String</td>
      <td>this.$tools.isString('字符串')</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isNumber()  &nbsp;&nbsp;&nbsp;&nbsp;是否数字</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>数字</td>
      <td>Number</td>
      <td>this.$tools.isNumber(123)</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isBoolean()  &nbsp;&nbsp;&nbsp;&nbsp;是否boolean</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>boolean</td>
      <td>boolean</td>
      <td>this.$tools.isBoolean(true)</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isFunction()  &nbsp;&nbsp;&nbsp;&nbsp;是否函数</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>函数</td>
      <td>Function</td>
      <td>this.$tools.isFunction(() => {})</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isNull()  &nbsp;&nbsp;&nbsp;&nbsp;是否为null</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>null</td>
      <td>all</td>
      <td>this.$tools.isNull(null)</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isUndefined()  &nbsp;&nbsp;&nbsp;&nbsp;是否undefined</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>all</td>
      <td>all</td>
      <td>this.$tools.isUndefined(undefined)</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isObj()  &nbsp;&nbsp;&nbsp;&nbsp;是否对象</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>对象</td>
      <td>Object</td>
      <td>this.$tools.isObj({test: 123})</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isArray()  &nbsp;&nbsp;&nbsp;&nbsp;是否数组</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>数组</td>
      <td>Array</td>
      <td>this.$tools.isArray([1,2,3])</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isDate()  &nbsp;&nbsp;&nbsp;&nbsp;是否时间</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>时间</td>
      <td>Date</td>
      <td>this.$tools.isDate(new Date())</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isError()  &nbsp;&nbsp;&nbsp;&nbsp;是否错误对象</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>错误</td>
      <td>Error</td>
      <td>this.$tools.isError(new Error())</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isSymbol()  &nbsp;&nbsp;&nbsp;&nbsp;是否Symbol函数</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>Symbol</td>
      <td>Symbol</td>
      <td>this.$tools.isSymbol(Symbol("test"))</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isPromise()  &nbsp;&nbsp;&nbsp;&nbsp;是否Promise对象</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>Promise</td>
      <td>Promise</td>
      <td>this.$tools.isPromise(new Promise(() => {}))</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isSet()  &nbsp;&nbsp;&nbsp;&nbsp;是否Set对象</td>
    </tr>
    <tr>
      <td>参数</td>
      <td>类型</td>
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <td>Set</td>
      <td>Set</td>
      <td>this.$tools.isSet(new Set())</td>
      <td>Boolean</td>
    </tr>
    <tr>
      <td colspan="4">isWeiXin()  &nbsp;&nbsp;&nbsp;&nbsp;是否是微信浏览器</td>
    </tr>
    <tr>
      <!-- <td>参数</td>
      <td>类型</td> -->
      <td>事例</td>
      <td>返回值类型</td>
    </tr>
    <tr>
      <!-- <td></td>
      <td></td> -->
      <td>this.$tools.isWeiXin()</td>
      <td>Boolean</td>
    </tr>
  </table>

