# 🔀 조건문 (if)

```bash
#!/bin/bash
num=5

if [ $num -gt 0 ]; then
  echo "양수입니다."
else
  echo "0 또는 음수입니다."
fi
```

## 📌 비교 연산자

| 연산자 | 설명 |
|--------|------|
| `-eq`  | 같다 |
| `-ne`  | 같지 않다 |
| `-gt`  | 크다 |
| `-lt`  | 작다 |
| `-ge`  | 크거나 같다 |
| `-le`  | 작거나 같다 |