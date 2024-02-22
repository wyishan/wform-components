# 介绍

w-form是一款基于uniapp+vue3的表单组件库。

它相较传统表单组件会更加简洁方便，相较低代码组件又更加灵活。



### 未完善

当前组件库大部分已开发完成，但组件完整度、使用文档、代码包大小优化都还没做完，所以不建议投入重要项目中使用。—— 2024年2月21日



### 使用文档下载

[http://154.8.162.215:8082/w-form表单组件使用文档.zip](http://154.8.162.215:8082/w-form表单组件使用文档.zip)



### 安装

第一步、将插件代码并放入项目根目录下。

第二步、在`pages.json`中配置以下片段即可。

```json
  {
    ...
    "easycom": {
      "custom": {
        "^w-(.*)": "@/wform-components/components/w-$1/w-$1.vue"
      }
    }
  }
```



### depend 文件夹、libs文件夹来自第三方

depend 文件夹及libs文件夹里的代码来自uview-plus、dayjs、async-validator等库。以后会把这些代码分离出去。



