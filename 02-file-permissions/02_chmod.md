# 🛠️ chmod: 권한 변경

## 📌 기본 사용법

```bash
chmod [옵션] [권한] [파일명]
```

## 📌 숫자 방식 예시

```bash
chmod 755 script.sh
```

- 사용자: rwx (7)
- 그룹: r-x (5)
- 기타: r-x (5)

## 📌 기호 방식 예시

```bash
chmod u+x file.sh
chmod go-w file.txt
```

- `u`: 사용자(user)
- `g`: 그룹(group)
- `o`: 기타(other)
- `a`: 전체(all)