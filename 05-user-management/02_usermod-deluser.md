# 🔧 사용자 수정 및 삭제

## 📌 사용자 속성 변경

```bash
usermod -l newname oldname     # 사용자 이름 변경
usermod -d /new/home username  # 홈 디렉토리 변경
usermod -s /bin/zsh username   # 로그인 셸 변경
```

---

## 📌 사용자 삭제

```bash
deluser username
deluser --remove-home username
```

- 홈 디렉토리까지 함께 삭제하려면 `--remove-home` 옵션 사용