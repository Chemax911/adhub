# Старт проекта.

Инициализация гит репы

  git init

  echo "# adhub" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin git@github.com:Chemax911/adhub.git
  git push -u origin master

Создание ветки

  git branch <<name>>

Переключение на ветку

  git checkout <<name>>

Генерация ключей

  ssh-keygen

  cat ~/.ssh/id_rsa.pub

Клонирование репозитория

  git clone