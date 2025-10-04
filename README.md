---
# yaml-language-server: $schema=schemas/проект.schema.json
Object type:
    - Проект
Tag:
    - Учеба
Creation date: "2025-09-25T20:58:58Z"
Created by:
    - shq
Emoji: "\U0001F4C4"
id: bafyreigpkln3mqb6j257gm4uhopmmzzsm3zbjy4faiiutl6yyq732nro2u
---
# Подготовка   
Олимпиада по прикладной информатике   
# **HTML**
   
- [x] Базовые теги   
- [x] Подключение файлов   
- [ ] Продвинутые теги   
```
<!DOCTYPE html>
<html lang="en">
<head>
    <link href="style.css" rel="stylesheet"></link>
</head>
<body>
    <script src="script.js"></script>
</body>
</html>

```
 --- 
# **CSS**   
- [x] Оцентровка   
- [x] Цвета, шрифты   
```
body {
    background-color: #f5f5f5;
    text-align: center; /* оцентровка */
    font-size: 16px; /* размер шрифта */
    font-family: Ubuntu, sans-serif;
}
ol {
    display: inline-block; /* блок со списков */
    text-align: left; /* вырав. списка */
}

a:hover { /* при наведении */
    color: green; 
}
```
 --- 
# JavaScript   
- [ ] if else   
- [ ] Циклы   
- [ ] WEB-дизайн (Listener, document и тд)   
```
const colors = ["red", "green", "blue","yellow", "purple"]

document.getElementById("colorButton").addEventListener("click", () => {
        document.body.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)]
    }
)
```
# **Администрирование на Linux**
   
find, pkill, systemctl, firewalld (firewall-cmd)   
# **Python**
   
- [ ] CLI-интерфейс   
- [ ] os, sys   
- [ ] ввод-вывод   
- [ ] работа с args   
- [ ] обработка ошибок (exceptions)   
- [ ] JSON   
- [ ] свое СУБД на JSON   
- [ ] кеширования при рекурсии   
