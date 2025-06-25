
### **Практические задания: Работа с файлами**

#### **1. Команда `touch`**
```bash
# Задание 1.1: Создать пустой файл
touch document.txt

# Задание 1.2: Создать несколько файлов сразу
touch file1.txt file2.txt file3.log

# Задание 1.3: Обновить временную метку существующего файла
touch document.txt
```

#### **2. Команда `mkdir`**
```bash
# Задание 2.1: Создать директорию
mkdir my_project

# Задание 2.2: Создать вложенные директории одной командой
mkdir -p project/{docs,src,backup}

# Задание 2.3: Создать директорию с пробелом в имени
mkdir "My Documents"
```

#### **3. Команда `cp`**
```bash
# Задание 3.1: Скопировать файл
cp document.txt document_backup.txt

# Задание 3.2: Скопировать файл в директорию
cp document.txt my_project
cd my_project
ls -al
cd ..

# Задание 3.3: Рекурсивное копирование директории
cp -r my_project/ new_my_project/
cd new_my_project
ls -al
cd ..
```

#### **4. Команда `mv`**
```bash
# Задание 4.1: Переименовать файл
mv document.txt new_document.txt
ls

# Задание 4.2: Переместить файл в другую директорию
mv new_document.txt project
cd project
ls
```

#### **5. Команда `rm`**
```bash
# Задание 5.1: Удалить файл
rm new_document.txt
ls
cd ..

# Задание 5.2: Удалить пустую директорию
ls
rmdir "My Documents"
ls
```

#### **Комбинированные задания**
```bash
# Задание 6.1: Создать структуру проекта
mkdir -p website/{css,js,images} && touch website/index.html
ls
cd website
ls
cd ..
```
