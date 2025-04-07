# 📦 변수 사용법

```bash
#!/bin/bash
name="Jongmin"
echo "Hello, $name"
```

- 변수 선언 시 `=` 앞뒤 공백 없어야 함
- `$변수명`으로 참조
- 따옴표로 묶어서 출력하는 게 안전

```bash
#!/bin/bash
readonly school="OpenAI"
echo $school
```

- `readonly`: 읽기 전용 변수