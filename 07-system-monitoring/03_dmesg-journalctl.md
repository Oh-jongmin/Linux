# 📜 부팅 로그 및 시스템 로그 확인

## 📌 dmesg

```bash
dmesg | less
```

- 커널 메시지 출력
- 하드웨어, 네트워크 장치 부팅 로그

---

## 📌 journalctl (systemd)

```bash
journalctl -xe
journalctl -u ssh
```

- systemd 기반 로그 확인
- `-xe`: 최근 에러 로그 중심 출력
- `-u`: 특정 서비스 로그 확인