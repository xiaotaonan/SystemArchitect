# 结构化设计⭐️⭐️⭐️⭐️

## 分类

### 概要设计【外部设计】

功能需求分配给软件模块，确定每个模块的功能和调用关系，形成模块结构图。

### 详细设计【内部设计】

为每个具体任务选择合适的技术手段和处理方法。



## 原则

### 模块独立性原则（高内聚、低耦合）

#### 内聚的类型

* 功能内聚：完成一个<mark style="color:$danger;">单一功能</mark>，各个部分协同工作，缺一不可
* 顺序内聚：处理元素相关，而且必须<mark style="color:$danger;">顺序执行</mark>
* 通信内聚：所有处理元素集中在一个<mark style="color:$danger;">数据结构的区域</mark>上
* 过程内聚：处理元素相关，而且必须按特定的次序执行
* 时间/瞬时内聚：所包含的任务必须在<mark style="color:$danger;">同一时间间隔</mark>内执行
* 逻辑内聚：完成<mark style="color:orange;">逻辑上相关</mark>的一组任务
* 偶然/巧合内聚：完成一组没有关系或松散关系的任务

### 保持模块的大小合适

### 多扇入，少扇出

### 深度和宽度均不宜过高



<img src="../../.gitbook/assets/file.excalidraw.svg" alt="" class="gitbook-drawing">

