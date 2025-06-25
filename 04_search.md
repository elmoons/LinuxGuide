### **Практические задания: Поиск**

#### 1. Базовый поиск текста (`grep`)
```bash
# Задание 1.1: Найти слово "error" в файле
grep "заметки" notes.txt

# Задание 1.2: Поиск без учета регистра
grep -i "ЗаМЕтКи" notes.txt

# Задание 1.3: Инвертированный поиск (строки которые НЕ содержат)
grep -v "записки" notes.txt
```

#### 2. Рекурсивный поиск (`grep -r`)
```bash
# Задание 2.1: Найти все вхождения "" в файлах проекта
mkdir test
cd test
touch {test1.txt,test2.txt,test3.txt}

echo "Hello" > test1.txt
echo "World" > test2.txt
echo "Hello World" > test3.txt

cd ~

grep -r "Hello" ~/test
```

#### 3. Поиск файлов (`find`)
```bash
# Задание 3.1: Найти все .txt файлы в домашней директории
find ~ -type f -name "*.txt"

# Задание 3.2: Найти директории с именем "test" в домашней директории
find ~ -type d -name "test"
```