# 👤 chown: 소유자 변경

## 📌 기본 사용법

```bash
chown [새소유자] 파일명
chown [소유자]:[그룹] 파일명
```

## 📌 예시

```bash
chown john file.txt
chown john:dev file.txt
```

> ⚠️ chown 명령은 root 권한이 필요할 수 있음 (`sudo chown ...`)