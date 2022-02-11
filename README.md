## [Common Lisp 笔记](https://common-lisp.net/)

### [SLIME: Emacs 的高级 Lisp 交互模式](https://slime.common-lisp.dev/)
> 手册
>
> [version 2.24](https://slime.common-lisp.dev/doc/html/) [SLIME’s 文档](https://slime-user-manual-cn.readthedocs.io/en/latest/) 

### [Steel Bank Common Lisp (SBCL) ](http://www.sbcl.org/)（Windows）

> 环境搭建
> 
> [在 Emacs 中安装 `SLIME SBCL Quicklisp`](https://eason0210.github.io/post/install-slime-sbcl-quicklisp/)

> [SBCL 快速上手教程](https://lisp-lang.org/learn/getting-started/)

> 手册
>
> [SBCL 文档](http://www.sbcl.org/manual/)

### [Clozure CL (often called CCL for short) ](https://ccl.clozure.com/)（Mac OS X）

> 环境搭建
> 
> [使用最新版 `Emacs Slime CCL` 建立 `Common Lisp IDE`](https://herculesshek.github.io/blog/2013/11/24/build-slime-emacs-clozureCL)

> 手册
>
> [Clozure CL 文档](https://ccl.clozure.com/docs/ccl.html)

### [Emacs](https://github.com/xingangshi/emacs_evil) ELPA 源
> [清华 - ELPA 镜像使用帮助](https://mirrors.tuna.tsinghua.edu.cn/help/elpa/)
```emacs
(setq package-archives '(("gnu"   . "http://mirrors.tuna.tsinghua.edu.cn/elpa/gnu/")
                         ("melpa" . "http://mirrors.tuna.tsinghua.edu.cn/elpa/melpa/")))
(package-initialize) ;; You might already have this line
```

> [腾讯 - ELPA源帮助文档](https://mirrors.cloud.tencent.com/help/elpa.html)
```emacs
(setq package-archives '(("gnu"   . "http://mirrors.cloud.tencent.com/elpa/gnu/")
                         ("melpa" . "http://mirrors.cloud.tencent.com/elpa/melpa/")))
(package-initialize) ;; You might already have this line
```

### 其他资料
- [Emacs 入坑笔记 - Common Lisp (Slime) 快捷键](https://shixiongfei.com/learn-emacs.html#org064fcce)
