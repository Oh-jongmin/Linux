# 🔍 포트 및 연결 상태 확인

## 📌 netstat

```bash
netstat -tuln
```

- 열려 있는 포트 및 연결 상태 확인
- `-t`: TCP / `-u`: UDP / `-l`: Listening / `-n`: 숫자 출력

---

## 📌 ss (netstat 대체 명령어)

```bash
ss -tuln
```

- `ss`: netstat보다 빠르고 간단함