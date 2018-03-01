## **2/27 Tuesday**

将Win10输入法快捷键更改为Ctrl+Shift, 切换语言, Ctrl+Space无法更改, 保留为切换键盘Layout.

Gitbook与GitHub连接失败, 原因是GitHub已经绑定另一个账户. 应该是之前用GitHub账户登录过.

家里笔记本follow公司电脑禁掉了不必要的第三方服务, 安装VS Code, 安装Python, 搜狗输入法, 调整输入法快捷键.

发现可以添加英语作为第二语言包并调整页面语言, 使其与公司电脑显示一致.

需要复查如何禁用搜狗网络服务.

---

## **2/28 Wednesday**

在公司电脑上安装GitBook Editor, 还是无法登陆, 网络禁止.

安装GitBook时遇到了以下问题. 网上找到solution已经解决.

> Fix – “This app can’t run on your PC” Windows 10 AMD
>
> **Solution – Download the application again using a different web browser**
>
> Number of users reported\_“This app can’t run on your PC”\_error message while trying to install AMD graphic card drivers. Apparently, the problem was caused by corrupted download, and after switching to a different browser and redownloading the same file again the issue was permanently resolved.

使用搜狗输入法在分屏打字时主屏右下角闪烁, 无法解决, 查询是与Chrome的兼容性问题. 实测在主屏上也有这个问题. 垃圾搜狗.

尝试改用Edge作为打开Gitbook的默认浏览器, 十分卡顿, 没法用.

Gitbook doesn’t have an app available on iOS platform. No third party support either.

Download and install xshell on work laptop. and WinSCP. And WireShark. And iSlide.

下午Team二月份生日会, 吃了蛋糕, 贝莱松, 很好吃.

---

## 2/29 Thursday

早晨登了三十多分钟椭圆机, 今天的训练量可以了.

#### Byte of Python

Literal Constants includ string and numbers.

Single and double quotes works exactly the same way.

There's no char in Python.

```py
import sys  # To use sys.stdout, this is necessary.

# Format Method of a string. 
phrase = '{0} is {1} years old'.format('Derek', 20) # 0 and 1 can be ommitted.
print(phrase)
# More format styles
print('{0:.3f}'.format(1.0/3)) # To specify precision of a float number.
print('{:.3f}'.format(1.0/3)) # 0 can be ommited.
print('{0:_^11}'.format('hello')) # Fill with _ to 11 length.
print('{name} wrote {book}'.format(name='Swaroop', book='A Byte of Python')) #use name.
print('{} wrote {}'.format('Swaroop', 'A Byte of Python')) # Omit style.

# print full definition.
print('Hello World', sep=' ', end='\n', file=sys.stdout, flush=False)

# Escape Sequences
print('What\'s your name?')
print("What's your name?")
print("""What's your name?""")
print('This is the first sentence. \
This is the second setence.')
print(r"What\'s your name?")
```

Can we access markdown version of 'Byte of Python'? Yes, but many .md files.

比较困, 趴着休息一会, 恢复过来了. 可以继续了.

曹方-遇见我

尝试使用修改路由的方式解决GitBook无法连接网络的问题, 使其优先连接到iPhone网络中, 失败, 因为即使可以登录, 笔记本也打不开.



