Создал джобы как в семинаре, прописал environments **preprod** и **production** и переменные **MY_LOGIN**. Переменные **MY_PASSWORD** созданы через настройки проекта в gitlab:

![](preprodvar.png)

Для окружения **production** сделаны аналогичные настройки.

Код файла **YAML**`.gitlab-ci.yml`:

![](yaml.png)

Пайплайн:

![](pipeline.png)

Сама джоба:

![](job.png)