# 🧩 함수 사용

```bash
#!/bin/bash
greet() {
  echo "안녕하세요, $1님!"
}

greet "종민"
```

- 함수 정의는 `함수명()` 또는 `function 함수명`
- `$1`, `$2` 등은 함수 인자