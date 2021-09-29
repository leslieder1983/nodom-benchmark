# nodom-benchmark

src目录存放测试代码

## 测试项目

###  编译单独测试



* 少量节点编译 (10个节点)

* 中量编译节点（100个节点）

* 大量编译节点（1000个节点）

* 极大量编译节点（1w+）



### 编译渲染同步测试

#### 基本测试（10个节点）

文件所处目录：**src/ten**



| 测试项目                       | 所在目录           |
| ------------------------------ | ------------------ |
| 普通渲染                       | /OrdinaryRendering |
| 替换所有节点                   | /ReplaceAll        |
| 部分更新（每十行更新一个数据） | /update            |
| 排序 随机节点                  | /randomUpdate      |
| 删除一行                       | /delete            |
| 删除所有行                     | /deleteAll         |







#### 中量节点（100个节点）

文件所处目录：**src/hundred**



| 测试项目                       | 所在目录           |
| ------------------------------ | ------------------ |
| 普通渲染                       | /OrdinaryRendering |
| 替换所有节点                   | /ReplaceAll        |
| 部分更新（每十行更新一个数据） | /update            |
| 排序 随机节点                  | /randomUpdate      |
| 删除一行                       | /delete            |
| 删除所有行                     | /deleteAll         |





#### 大量节点（1000个节点）

文件所处目录：**src/thousand**



| 测试项目                       | 所在目录           |
| ------------------------------ | ------------------ |
| 普通渲染                       | /OrdinaryRendering |
| 替换所有节点                   | /ReplaceAll        |
| 部分更新（每十行更新一个数据） | /update            |
| 排序 随机节点                  | /randomUpdate      |
| 删除一行                       | /delete            |
| 删除所有行                     | /deleteAll         |

#### 极大量节点（10000+个节点）

文件所处目录：**src/myriad**



| 测试项目                       | 所在目录           |
| ------------------------------ | ------------------ |
| 普通渲染                       | /OrdinaryRendering |
| 替换所有节点                   | /ReplaceAll        |
| 部分更新（每十行更新一个数据） | /update            |
| 排序 随机节点                  | /randomUpdate      |
| 删除一行                       | /delete            |
| 删除所有行                     | /deleteAll         |
