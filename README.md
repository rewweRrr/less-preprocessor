# Less песочница

https://lesscss.org/

## Начало работы

1. Созайте файл index.html

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
</body>

</html>
```

2. Создайте файл __styles.less__
3. Подключите стили в __\<head\>__

```
<link rel="stylesheet/less" type="text/css" href="styles.less" />
<script src="https://cdn.jsdelivr.net/npm/less" ></script>
```

## Альтернативный вариант

1. Установите глобально зависимости

```
npm install -g less
```

2. Скомпилируйте __less__ в __css__

```
lessc styles.less styles.css
```

3. Подключите полученный __styles.css__ в __index.html__
