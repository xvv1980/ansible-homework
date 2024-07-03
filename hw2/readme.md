### Процесс запуска доработаного playbook с результатом:

#### Запуск созданного playbook
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/99dd9eea-901c-4d0d-aa30-2b36c23f27c9)
#### Проверяем запущенные модули clickhouse-server и vector на managed-host
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/80e75277-3597-4930-9ee7-3839e13bbda9)

### Скриншоты пп 5-8
#### 5. ansible-lint site.yml.  
Видим различные синтакс. и прочие ошибки
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/063a675a-0b67-44e9-af7c-fd9ff9d5f666)
Исправляем
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/618802e2-6c47-4e04-b183-229215ca11f9)

#### 6. ansible-playbook -i inventory/prod.yml site.yml --check
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/86adaff2-4329-4a3f-bcbe-1e81e2ed9298)

#### 7. ansible-playbook -i inventory/prod.yml site.yml --diff
Видим внесенные изменения
![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/6ac0d707-b533-4bdd-9afb-c6b2bb826313)

#### 8. ansible-playbook -i inventory/prod.yml site.yml --diff
Playbook идемпотентен

![изображение](https://github.com/xvv1980/ansible-homework/assets/169840386/5e9ccc1c-ceda-441d-a2cd-e61025d6c45c)





