# 🌐 네트워크 연결 확인: ping & traceroute

## 📌 ping

```bash
ping google.com
ping -c 4 naver.com
```

- 호스트에 패킷을 보내 응답 시간 확인
- `-c [횟수]`: 지정된 횟수만큼 요청

---

## 📌 traceroute

```bash
traceroute google.com
```

- 목적지까지 거치는 라우터 경로 추적
- Windows에서는 `tracert` 사용