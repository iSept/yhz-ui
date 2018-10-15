# YHZ-UI

> YHZ-UI Components for Vue.js


## DOC - (Confirm)
### 属性
| 名称                   |  类型    |  默认值        |  说明                                 |
| --------              |  :-----: |  -----         | ----                                  |
| value                 |  boolean |  false         |   是否显示                            |
| confirmStyle          |  boolean |  1             |   确认框风格，可取值1,2                |
| title                 |  string  |  提示          |   标题，confirmStyle为2生效            |
| titleImage            |  string  |                |  头部图片，confirmStyle为1失效         |
| titleImageStyle       |  Object  |                | 头部图片样式，confirmStyle为1失效      |
| content               |  string  |                | 弹框内容                              |
| confirmText           |  string  |  确定           | 确定按钮文案                          |
| cancelText            |  string  |  取消           | 取消按钮文案                          |
| confirmButtonPosition |  string  |  right          | 确认按钮位置取值：left,right会显示2个按钮，center只会显示一个按钮 |
| showConfirmButton     |  boolean |  true           | 是否显示确定按钮                       |
| showCancelButton      |  boolean |  true           | 是否显示取消按钮, 确认按钮位置为center时失效 |
| closeOnConfirm        |  boolean |  true           | 是否在点击确认按钮时自动关闭确认框      |
| hideOnBlur            |  boolean |  true           | 是否在点击遮罩时自动关闭弹窗           |
| maskTransition        |  string  |  yinhe-mask     | 遮罩动画                              |
| dialogTransition      |  string  |  yinhe-dialog   | 弹窗主体动画                          |
| dialogClass           |  string  |  yinheui-dialog | 弹框主体class                         |
| dialogStyle           |  object  |                 | 弹框主体样式                          |
| maskZIndex            |  number,string | 1000      | 遮罩层 z-index 值                     |

### 方法
| 名称                   |  说明             |
| --------               |  -----           |
| @on-confirm            | 点击确定按钮时触发 |
| @on-cancel             | 点击取消按钮时触发 |
| @on-show               | 弹窗出现时触发     |
| @on-hide               | 弹窗隐藏时触发     |


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
