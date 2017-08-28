# K-Top Components

## 组件说明
### layout
* layout - ng 基础布局
* layout.grid - ok 栅格布局
### element
* element.color - ok 颜色描述
* element.button - ok
* element.icon - ok 引入了
* element.font - ng 自定义字体 
### view
* view.table - ng 基础表格展示
* view.box - ok 包含表格的一块区域
* view.window - ok
* view.message - ok
* view.dialog - ok
* view.alert - ng 警告提示
* view.notice - ng
* view.modal  - ng
* view.tooltip  - ng
* view.progress - ok 仅有 css
* view.tag - ng 
* view.collapse - ng 伸缩面板
* view.card - ng 卡片
### form
* form.text - ok
* form.textbox - ok
* form.numberBox - ok
* form.combo - ok
* form.comboBox - ok
* form.radio - ok
* form.checkbox - ok
* form.numberSpinnerBox - ok
* form.select - ng 下拉选择
* form.select.cascader - ng 级联下拉选择
* form.select.autocomplete - ng 自动完成
* form.switch - ng
* form.rate - ng 评分
* form.slider - ng
* form.dataPicker - ng
* form.timePicker - ng
* form.transfer - ng 穿梭框
### navigation
* nav.tab - ok 标签页
* nav.pager - ok
* nav.badge - ok 仅有 css
* nav.button - ok
* nav.menu - ok
* nav.dropmenu - ng 下拉菜单
* nav.popup - ok
* nav.tip - ok
* nav.box - ok
* nav.breadcrumb - ng 面包屑导航
* nav.loadingBar - ng
* nav.steps - ng 步骤
### panel 系统总体结构
* panel.dock.js - ok
* panel.top.js - ok
* panel.nav.js - ok
* panel.main.js - ok
* panel.foot.js - ok
* panel.left.js - ok
* panel.right.js - ok
* panel.center.js - ok
* panel.mapTool.js - ok
* panel.map.js - ok
* panel.bottom.js - ok
* panel.fill.js - ok
* panel.menuInit.js - ok
### ucmap 地图相关
* ucmap.tool
* ucmap.menu
* ucmap.switch
* ucmap.timeline
* ucmap.legend 
* ucmap.waitbox
* ucmap.tip
### module
* module.tree - ok 树
* module.datagrid - ok
* module.upload - ng
* module.calendar - ng 日历
* module.accordion - ng 
* module.code - ng 代码高亮显示
* module.carousel - ng 轮播
* module.editor - ng 富文本编辑器
* module.timeline - ng 时间线
### other
* other.animation - ok 动画
* other.backTop - ng 返回顶部
* other.spin - ng 加载中
* other.local - ng 多语言
* other.theme - ng 主题
* other.customComponent - ng 自定义组件
### chart
* chart.pie 饼图
* chart.line 折线图
## 改进
* 集成代码打包,自动化打包 - ok
* 布局及原始的组件进行分离 - ok
* 设置哪些文件夹及文件不进行提交 - 
* 原始组件分类，标注不需要的组件 - ing
* 统一编码格式，并进行标识 - ing
* 加入单元测试 - ng
* 控件按需加载 - ng 优先级低
* 编码规范及优秀实践 - ing 
* jQuery 升级，ES6提高效率 - ng
* 扩展 html 语义标签 - ng
## 扩展
* 栅格系统 - ok
* 动画效果扩展 - ok
* 字体模式扩展 icon - ok
* ？？MVC，抽取数据模型 - ng
* ？？界面表达，模板引擎 - ng
* ？？订阅消息广播 - ng