# Fastcampus Data Science SCHOOL
## git

---
<!--
page_number: true
$size: A4
footer : fastcampus 데이터 사이언스 스쿨, Wooyoung Choi, 2017
-->

![](http://ipengineer.net/wp-content/uploads/2015/04/git-logo.jpg)

---
## Goal
- git을 이해하고, git과 github이 다름을 인지한다
- git을 활용하여 나의 소스코드를 관리할 수 있다
- 데이터 사이언티스트의 커리어를 스웩할 나만의 멋진블로그를 만들 수 있다
- git의 branch model을 활용해 능숙하게 코드관리할 수 있다
- git으로 타인과 협업하며, 다른 포르젝트에 기여할 수 있다

---
## Goal
- ~~git을 이해하고, git과 github이 다름을 인지한다~~
- ~~git을 활용하여 나의 소스코드를 관리할 수 있다~~
- ~~데이터 사이언티스트의 커리어를 스웩할 나만의 멋진블로그를 만들 수 있다~~
- git의 branch model을 활용해 능숙하게 코드관리할 수 있다
- git으로 타인과 협업하며, 다른 포르젝트에 기여할 수 있다

---
## Assignment
Try git

---
## What is branch?

---
## What is branch?
![](https://www.sideshowtoy.com/assets/products/3005011-groot/lg/marvel-guardians-of-the-galaxy-groot-premium-format-3005011-02.jpg)

---
## What is branch?
분기점을 생성하고 독립적으로 코드를 변경할 수 있도록 도와주는 모델

ex)

master branch
```python
print('hello world!')
```

another branch
```python
for i in range(1,10):
    print('hello world for the %s times!' % i)
```


---
## Branch

Show available local branch
`$ git branch`

Show available remote branch
`$ git branch -r`

Show available All branch
`$ git branch -a`

---
## Branch

Create branch
`$ git branch stem`

Checkout branch
`$ git checkout stem`

**OR**

Create & Checkout branch
`$ git checkout -b new-stem`

---
## Branch
make changes inside readme.md
`$ git add readme.md`
`$ git commit -m 'edit readme.md'`
`$ git push origin stem`

---
## Branch

push with specified remote branch
`$ git push origin stem`

see the difference between two branches
`$ git diff master stem`

merge branch
`$ git merge stem`

delete branch
`$ git branch -D stem`

---
## git flow strategy
![](https://media.licdn.com/mpr/mpr/shrinknp_800_800/AAEAAQAAAAAAAAKMAAAAJDM2NjY0OWE4LTc0NDAtNDdkMS1hMDdiLWU3MzkwM2FjYWExNw.png)

---
## use git flow easily!
[Link](https://danielkummer.github.io/git-flow-cheatsheet/index.ko_KR.html)

![](https://danielkummer.github.io/git-flow-cheatsheet/img/git-flow-commands.png)

---
## Collaborate with your Co-worker

---
## Method 1: Collaboration
Add Collaborator
![](../img/collaborators.png)

---
## Collaboration
Add, Commit and Push like you own it. 

---
## Method 2: Fork and Merge
![](../img/fork1.png)

---
## Fork and Merge
![](../img/fork2.png)

---
## Fork and Merge
![](../img/fork3.png)

---
## Fork and Merge
`$ git clone https://github.com/username/forked-repo.git`
`$ git remote add upstream https://github.com/anotheruser/original-repo.git`

---
## Fork and Merge

`$ git fetch upstream`
`$ git merge upstream/master`
`$ git branch -a`
`$ git checkout -b new-feature`

---
## Fork and Merge

Make some change

`$ git add file`
`$ git commit -m "commit message"`
`$ git push origin new-feature`

---
## Fork and Merge
![](../img/pr1.png)

---
## Fork and Merge
![](../img/pr2.png)

---
## Fork and Merge
![](../img/pr3.png)

---
## Fork and Merge
![](../img/pr4.png)

---
## Fork and Merge
![](../img/pr5.png)

---
## Fork and Merge
![](../img/pr6.png)

---
## Fork and Merge
![](../img/pr7.png)


---
![](../img/thankforme.jpg)