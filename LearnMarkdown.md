 <h1 style="color:blue;text-align:center">标题</h1>

# 一级标题
## 二级标题
1. **引用**
    >引用
    >>嵌套引用
2. **列表**
   1. 无序列表
   - list1
   - list2
   + list3
   * list4
   1. 有序列表
      1. list1
      2. list2
   2. 嵌套
      1.   list1
           1.   list01
   3. ToDolist
       - [ ] a
       - [ ] b
       - [ ] c
   4. 标记
       - H~2~O, e^2^ 
3. **表格**
    | 左对齐 | 居中对齐 | 右对齐 |
    | :----- | :----: | -----: |
    | a | b | c |
4. **段落**
   - 换行 - 两个以上空格后回车 / 空一行  
    这样
   - 分割线 - 三个*
    ***
   - 字体
        | 字体 | 代码 |
        | :-: | :-: |
        |*斜体*|* *|
        |==高亮==|== ==|
        |**粗体**|** **|
        |***斜粗体***|*** ***|
        |~~删除~~|~~ ~~|
        |<u> 下划线 </u>|```<u> </u>```|
   - 脚注
        论文在这里[^1]看
5. **代码**
   ```cpp
   #include <iostream>
   using namespace std;
   const int maxn = 1e5;
   signed main(void){
        cout << "Hello World!" << endl;
        return 0;
   }
   ```
6. **超链接**
    [可参考](https://www.bilibili.com/video/BV1bK4y1i7BY"Markdown视频链接")
    [点击链接][教程]
7. **图片**
   - 使用 [图床]: https://imgse.com/
   - ![百度](https://pss.bdstatic.com/static/superman/img/logo/logo_white-d0c9fe2af5.png)
### **插入公式**
- latex
  - 行内: $ f(x) = ax + b$
  - 块内:
  $$
  \begin{Bmatrix}
  a & b \\
  c & d
  \end{Bmatrix}
  $$
- html/CSS 实现多样化
- Preference-Settings可设置默认Markdown行间距
- 导出 :
  1. 在浏览器里打开
  2. 保存

[教程]: https://www.bilibili.com/video/BV1bK4y1i7BY
[^1]:跳转

