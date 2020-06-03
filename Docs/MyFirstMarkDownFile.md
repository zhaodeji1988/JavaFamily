[toc]

# 一、标题

列表是一级标题：在标题的前面加#和一个空格

## 我是二级标题

在标题的前面加##和一个空格

### 我是三级标题

以此类推

# 一级标题的快捷键

ctrl+1

## 二级标题的快捷键

ctrl+2

### 三级标题的快捷键

ctrl+3以此类推

# 二、字体格式

1. *斜体文本*

   在文字两边加*

2. **粗体文本**

   在文字两边加**

3. ***斜粗体文本***

   在文字两边加***

4. 分割线

   在空行中使用三个以上的*、---、___。*

   这是三个*

   ***

   这是三个---

   ---

   这是三个___

   ___

5. 删除线

   在文字两边加~~

   ~~删除线~~

6. 下划线：在文字两边加<u></u>

   <u>下滑线</u>

---

7. 添加脚注

   使用[^XXX]添加脚注

   我爱吃苹果[^脚注1]

[^脚注1]:这是脚注1的内容

---

# 三、列表

1. 无序列表

   无序列表使用*、+、-，作为标记。

   * 第一项
   * 第二项
   * 第三项
     * 第一项
     * 第二项
       * 第一项

2. 有序列表

   有序列表使用数字加上. 号作为标记。

   1. 第一项
   2. 第二项
   3. 第三项

3. 嵌套列表

   在有序列表中的子列表前添加四个空格

   1. 列表1
      * 子列表1
      * 子列表2

# 四、区块

* 列表中使用区块

  > * 列表1
  > * 列表2

* 区块中使用列表

> 1. 区块中的列表1
> 2. 区块中的列表2
> 3. 区块中的列表3

* 区块的嵌套

> 最外层区块
>
> > 第二层区块
> >
> > > 第三层区块

# 五、代码

* 段落中的代码：

  `System.out.println();`这个一句代码。

* 代码区块：

  ```java
  public String method() {
  	System.out.println("这是一段代码");
  	return null;
  }
  ```

# 六、链接

这是百度的链接[链接地址](www.baidu.com)

# 七、图片

<img src="C:\Users\Z\Pictures\redis冗余.png" alt="picture" style="zoom:67%;" />              <img src="C:\Users\Z\Pictures\平安喜乐.jpg" style="zoom:10%;" />    <img src="https://timgsa.baidu.com/timg?image&amp;quality=80&amp;size=b9999_10000&amp;sec=1591191277051&amp;di=ae5af561fead7bc48d75a3fc388ef1c6&amp;imgtype=0&amp;src=http%3A%2F%2Fpic4.zhimg.com%2Fv2-2a56e92cf72cd1268d299f47b8d2cf14_r.jpg" style="zoom:50%;" />



# 八、表格

|  表头1  |  表头2  |  表头3  |
| :-----: | :-----: | :-----: |
| 单元格1 | 单元格2 | 单元格3 |

# 九、高级功能

1. 标准流程图

~~~flow
```
st=>start: 数据迁移功能每天凌晨1点开始
op=>operation: 处理框
cond=>condition: 判断框(是或否?)
sub1=>subroutine: 子流程
io=>inputoutput: 输入输出框
e=>end: 结束框
st->op->cond
cond(yes)->io->e
cond(no)->sub1(right)->op
```
~~~



