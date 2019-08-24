# 公共组件

### 项目目录结构
> 每个页面一个文件夹  页面与页面之间不能存在依赖关系  要做到拿到既能用
  每个页面组件应有对应的 README.md 文件 该文件标明组件的功能 使用注意事项等组件作者需要让使用者知晓的信息


```
.
├── common                                    公共方法
    ├── styles                                           公共样式
    └── api                                              公共请求

├── components                                公共零件组件
├── src                                       页面
    ├── components                                       公共页面模块组件
    └── dev                                              开发预览

├── static                                    公共静态资源
├── .editconfig                               编辑器设置
├── .gitignore                                git忽略文件
└── pages.json                                页面配置
```
