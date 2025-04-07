# 📁 주요 시스템 파일

## 📌 /etc/passwd

- 사용자 계정 정보 저장
- 각 필드: 사용자명:x:UID:GID:설명:홈디렉토리:셸

```bash
cat /etc/passwd
```

## 📌 /etc/shadow

- 사용자 비밀번호 해시 정보 저장
- 보안상 root 권한 필요

```bash
sudo cat /etc/shadow
```

## 📌 /etc/group

- 그룹 정보 확인

```bash
cat /etc/group
```