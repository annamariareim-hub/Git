# 📌 Git

Git is a version control system available on every developer’s computer. It allows easy branching and merging. At the same time GitHub makes it a lot easier for individuals and teams to use Git for version control and collaboration 🤝

I am happy to share some git commands that I used to create my GitHub portfolio. 

## Easy navigation

- [Creating, cloning, pushing and pulling repositories](#task-1)
- [Creating, adding remote repositories](#task-2)

## Task 1

##### Creating, cloning, pushing and pulling repositories  
```git
git init osukhorukova                                       # Создать локальный репозиторий с именем, совпадающим с вашим GitHub-именем
git clone git@github.com:annamariareim-hub/annamariareim-hub.git      # Склонировать свой репозиторий на компьютер в отдельную папку
git clone git@github.com:testrusau/testrusau.git            # Склонировать репозиторий github.com/testrusau/testrusau на компьютер в отдельную папку
cd testrusau                                                # Перейти в папку testrusau
git push git@github.com:annamariareim-hub/testrusau.git main:main  # Отправить данные из репозитория testrusau в свой собственный репозиторий
git commit -m "описание внесённых изменений"                # Открыть файл README.md и внести изменения, закоммитив каждую часть отдельно
git push                                                    # Отправить коммиты в удалённый репозиторий
```
## Task 2

##### Creating, adding remote repositories  
```git
git init sql                                                # Создать отдельный локальный репозиторий для элемента портфолио (например, по SQL)
git remote add sql https://github.com/annamariareim-hub/sql.git  # Указать удалённый (remote) репозиторий на GitHub
# README.md отредактирован вручную                         # Вручную добавить ссылки на свои репозитории в файл README.md
git add README.md                                           # Добавить изменённый файл в индекс (stage)
git commit -m "описание внесённых изменений"                # Зафиксировать изменения
git push sql main                                           # Отправить изменения в удалённый репозиторий




```
