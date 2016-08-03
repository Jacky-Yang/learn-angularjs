# Developer Guide

## 概念概览

- 模板(Template)：带有Angular扩展标记的HTML
- 指令(Directive)：用于通过**自定义属性和元素**扩展HTML
- 模型(Model)： 用于显示给用户并且与用户互动的**数据**
- 作用域(Scope)：用于存储模型(Model)的上下文(context)。模型放在这个上下文中才能被控制器、指令、表达式等访问到
- 表达式(Expressiong)：模板中可以通过它来访问作用域(Scope)中的变量和函数
- 编译器(Compiler)：用来**编译**模板(Template)，并且对其中包含的指令(Directive)和表达式(Expression)进行**实例化**
- 过滤器(Filter)：负责**格式化**表达式(Expression)的值，以便呈现给用户
- 试图(View)：用户看到的内容(即**DOM**)
- 数据绑定(Data Binding)：**自动同步**模型(Model)中的数据和试图(View)表现
- 控制器(Controller)：视图(View)背后的**业务逻辑**
- 依赖注入(Dependency Injection)：负责创建和自动装载对象或函数
- 注入器(Injector)：用来实现依赖注入的容器
- 模块(Module)：一个包含应用程序各个部分，包括控制器、服务、过滤器、指令并且对注入器进行配置的容器
- 服务(Service)：独立于视图的、可复用的业务逻辑