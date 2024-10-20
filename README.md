# zeabur-django-celery-demo

在zeabur中运行基于django的celery

注意，需要在zbpack.json中配置下面命令才能启动celery，否则可能会启动django

```
{
    "start_command": "celery -A config worker -l INFO"
}
```

## 项目依赖

- python>=3.8
- rye
- django 5.1.2
- celery 5.4.0

参考资料：https://docs.celeryq.dev/en/stable/django/first-steps-with-django.html
