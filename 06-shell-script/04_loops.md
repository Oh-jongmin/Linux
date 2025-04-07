# 🔁 반복문 (for, while)

## 📌 for loop

```bash
#!/bin/bash
for i in 1 2 3
do
  echo "숫자: $i"
done
```

## 📌 while loop

```bash
#!/bin/bash
count=1
while [ $count -le 3 ]
do
  echo "반복: $count"
  ((count++))
done
```