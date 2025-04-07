# 🔐 파일 및 디렉토리 권한 개요

Linux에서는 모든 파일과 디렉토리에 **권한(Permission)**이 부여됩니다.

## 📌 권한의 구성

```bash
ls -l
```

출력 예시:
```
-rwxr-xr--
```

- 첫 문자: `-` (파일), `d` (디렉토리)
- 그 다음 9자리:
  - `r`(read), `w`(write), `x`(execute)
  - 사용자(owner) / 그룹(group) / 기타(other)

## 📌 숫자로 권한 표시

- `r = 4`, `w = 2`, `x = 1`
- 예: `chmod 755 file.txt` → `rwxr-xr-x`

| 숫자 | 의미 |
|------|------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |