学习django: https://docs.djangoproject.com/zh-hans/3.2/intro/tutorial01/

项目公网启动：python3 manage.py runserver 0:8000(建议：alias rs="python3 manage.py runserver 0:8000") 。为此需要在settings.py下的ALLOWED_HOSTS 加上公网ip，不然访问不了。
http://172.245.210.15:8000/