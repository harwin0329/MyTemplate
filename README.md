## This's Template Project!
## Happy Life! Happy Coding!

## 如何使用？

把下面这段代码加到 ` ~/.bash_profile ` 以后需要新建一个模块 只需要 createproject {projectName} 就可以了

```
createproject() {
  git clone git@gitee.com:qubukeji/MyTemplate.git $1
  cd $1
  python create.py $1
}

```
