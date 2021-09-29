# 원격저장소 활용

> 원격저장소 활용을 하기 위해서는 GitHub 사이트에서 직접 만들어야 한다.

## 원격저장소 등록

```bash
$ git remote add origin https://github.com/username/repository_name.git
```

* 깃아, 원격저장소(`remote`)를 추가해줘(add). `origin` 으로 `url`을

## 원격저장소 확인

```bash
$ git remote -v
origin  https://github.com/username/repository_name.git (fetch)
origin  https://github.com/username/repository_name.git (push)
```

## push

> 커밋을 원격저장소에 업데이트

```bash
$ git push origin master
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (8/8), 653 bytes | 653.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/edutak/first-0929.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

```



