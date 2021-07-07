提交记录

Revert 哪个“提交记录”这个“记录以及这个记录之后”的都没有了，但是 gitlab 那 revert 就只能消掉某一条 commit 

cherry-pick 是这个记录之后都没有了

但是 commit 记录有

aaa
bbb
ccc


git revert aaaa
修复冲突后，导致
aaa
bbb
ccc
都消失


git reset --hard fdf4d4a7e75985bce90e66517a7b3f7a00be7b02
显示
aaa
内容


git reset --hard 55fd4a6
回复到
```
aaa
bbb
ccc
```


```
echo "# 3333" >> README.md
git add README.md
git commit -m '333'
git push
```


git cherry-pick f93c22bca65581ad925af325f4b7acb5afdd4bac
git cherry-pick qqq
qqq 存在，



下一步：
Git reset 来回切换版本，


 src/components/chat-layer/index.tsx



