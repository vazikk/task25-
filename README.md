# task25-

Установка k3s: <br>
<br>
Из документации взял команду и вставил в терминал <br>

```curl -sfL https://get.k3s.io | sh -``` <br>

Проверка: <br>
```kubectl get nodes``` <br>

<img width="718" height="51" alt="image" src="https://github.com/user-attachments/assets/dc5958f0-bd22-4f94-b4b6-7692743b5ead" />
<br>

<br>

Установка Deckhouse: <br>
<br>
Подготовка: <br>
1) Надо для начала запустить instance где: <br>
RAM > 4 gb <br>
Memory > 10 gb <br>

2) Установить dokcer и добавить пользователя в группу docker <br>

Установка: <br>
Нашёл вариант установки через скрипт из github: <br>
```bash -c "$(curl -Ls https://raw.githubusercontent.com/deckhouse/deckhouse/main/tools/kind-d8.sh)"```

Итог: <br>
<img width="703" height="69" alt="image" src="https://github.com/user-attachments/assets/f3ee80d7-b26d-4f67-874a-bea648b7da60" />






