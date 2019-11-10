1. ![](./img/docker-say.png)
![](./img/my_worklog.png)

2. ![](./img/dockerpull.png)

створив Dockerfile та скопіював вміст та замінив репозиторій: ![](./img/dockerfile.png)

3. docker build -t mrzara/lab4-examples:django .
![](./img/dockerimages.png)
![](./img/dockerpush.png)
посилання на репозиторій: https://hub.docker.com/r/mrzara/lab4-examples

4. docker run -it --name=django --rm -p 8000:8000 mrzara/lab4-examples:django
![](./img/dockerrun.png)
![](./img/dockerrun-browser.png)

5. Створив ше файл Dockerfile та запустив докер
![](./img/homework.png)

6. Зробив коміт імеджів до репозиторію та витягнув логи створивши volume 