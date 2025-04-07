# 📝 파일 이름 변경 (rename 또는 mv)

## 📌 mv 사용

```bash
mv old.txt new.txt
```

- 가장 기본적인 리네이밍 방법
- 원본 파일이 새 이름으로 변경됨

## 📌 rename 명령어 (시스템에 따라 다름)

```bash
rename 's/.txt/.bak/' *.txt
```

- 확장자 일괄 변경 등 스크립트형 리네임
- 일부 Linux 배포판은 `rename` 미포함 (별도 설치 필요)