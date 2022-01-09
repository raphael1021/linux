## Dataset Definition

```shell
#/dev/zero 파일의 내용을 읽고 /test로 작성하는 것을 1Gi 크기로 20번 반복한다.
dd if=/dev/zero of=/test bs=1G count=20

/dev/xvda1       60G  3.2G   57G   6% /

20+0 records in
20+0 records out
21474836480 bytes (21 GB) copied, 148.227 s, 145 MB/s

/dev/xvda1       60G   23G   38G  37% /
```
