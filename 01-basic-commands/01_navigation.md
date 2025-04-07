# 📁 디렉토리 탐색 및 경로 확인

## 📌 현재 경로 확인
```bash
pwd
```

- 현재 작업 중인 디렉토리의 전체 경로 출력
- 예: `/home/user/project`

## 📌 디렉토리 이동
```bash
cd [경로]
```

- `cd /home` → 절대 경로로 이동  
- `cd ..` → 상위 디렉토리로 이동  
- `cd` → 홈 디렉토리로 이동

## 📌 디렉토리 생성
```bash
mkdir new-folder
mkdir -p a/b/c
```

- `-p`: 중간 디렉토리까지 한 번에 생성

## 📌 디렉토리 삭제
```bash
rmdir folder
rm -r folder
```

⚠️ `rm -rf /` 와 같은 명령은 매우 위험하므로 주의 필요!