# 📡 통신 테스트: curl & nc

## 📌 curl

```bash
curl http://example.com
curl -I https://naver.com
```

- 웹 서버 응답 확인
- `-I`: 헤더만 요청

---

## 📌 nc (netcat)

```bash
nc -zv google.com 80
```

- 포트 열려 있는지 확인 (port scan)
- `-z`: 연결 테스트만 / `-v`: verbose (출력)