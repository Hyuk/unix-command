# Unix Command

### alias

명령어를 다른 이름으로 바꿔서 별칭으로 사용할 수 있게 등록해주는 명령어

```bash
$ alias ll='ls -al'
```

이렇게 등록하면 `ll`이라고 입력하면 `ls -al`이 실행된다.

### unalias

alias로 등록한 명령어를 삭제하는 명령어

```bash
$ unalias ll
```

이렇게 하면 `ll`이라는 별칭이 삭제된다.

### cat

파일의 내용을 화면에 출력하는 명령어

```bash
$ cat file.txt
```

### pwd

현재 작업 디렉토리의 경로를 출력하는 명령어

```bash
$ pwd
```

### cd

디렉토리를 변경하는 명령어

```bash
$ cd /home/user
```

### ls

디렉토리의 파일 목록을 출력하는 명령어

```bash
$ ls
```

### ls -al

디렉토리의 파일 목록을 숨김 파일까지 모두 출력하는 명령어

```bash
$ ls -al
```

### cp

파일을 복사하는 명령어

```bash
$ cp file1.txt file2.txt
```

### mv

파일을 이동하거나 이름을 변경하는 명령어

```bash
$ mv file1.txt /home/user
```

### rm

파일을 삭제하는 명령어

```bash
$ rm file.txt
```

### rm -rf

디렉토리를 삭제하는 명령어

```bash
$ rm -rf directory
```

### mkdir

디렉토리를 생성하는 명령어

```bash
$ mkdir directory
```
