<!--
 * @Descripttion: 该页面用于——
 * @Author: zhanglinli
 * @Date: 2021-03-11 15:27:13
 * @LastEditors: zhanglinli
 * @LastEditTime: 2021-03-11 16:32:48
-->

> 由于未知需要，假定需求为增加控件类型与增加某个控件 change 导致第三种联动情况
> 增加控件类型即增加 itemType

` v-else-if="item.itemType === '增加的控件类型名称'"`

> 增加某个控件 change 导致第三种联动情况即增加配置属性如：`changeShow`，`changeProp`<br>
> 假定配置属性名为 `changeThree`，`changeTree` 内编写第三种级联逻辑部分

```javascript
if (changeThree) {
  // 处理第三种级联
}
```