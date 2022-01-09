## DiskUnit

```shell
# 용량 큰 순으로 10개 보기
du -shx * | sort -rh | head -n 10


# nginx log 용량 꽉 찰때 조치 방법
# 로그 파일 용량 확인
du -shx /var/log/nginx/* | sort -rh | head -n 10

# 로그파일 비우기
truncate -s 0 /var/log/nginx/access.log
```
