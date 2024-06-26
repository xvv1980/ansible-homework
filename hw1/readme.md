### 1.  
 #### Вывод переменной some_facts соответствует значению 12.
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/51de991a-fa98-4a15-a3a7-92e54c381c92)

### 2.
#### Здесь задавалась значение 12
  ![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/5205d4f7-2cd5-47b2-a6ef-8c221fae556d)

### 3.
#### Подготовлено окружение docker для ОС Alpine и Fedora. Имена контейнеров прописаны в inventory/prod. Под них созданы соответственно group_vars.
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/b4a2dd47-4b29-4e01-baf9-3c2403ef4937)

### 4. 
#### Вывод переменной some_facts соотв. значениям "alp" , "fed" для хостов alpine и fedora
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/3c48e0b2-1431-4078-aa86-caa3fc192335)

### 5.,6.
####  Изменены переменные some_facts для каждой группы хостов
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/ec4533f8-1f87-4f54-ab56-e414c4d6c576)

### 7.,8.
#### Зашифрованы содержимое переменных some_facts
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/1068e4e9-1b52-47d6-8b32-175291a9e951)
#### Запущен playbook, указан пароль, содержимое some_facts корректно
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/e78d306e-071b-44fa-aaba-af6b628557de)

### 9.
#### Просмотр документации
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/6851bfd5-3fd6-4f3c-a8c1-1a64457b99dd)

### 10. 
#### Добавление localhost
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/5eb7a9eb-490c-4249-bd01-aef4ca9b7ead)

### 11.
#### Все факты собрались из своих групп. Для localhost из группы all, так как для localhost переменная some_facts не была определена в отдельной группе.
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/a6497ef3-1523-42bf-adcf-f608594a5ada)










