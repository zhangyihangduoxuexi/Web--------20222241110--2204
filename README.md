# web大作业-张翼航-20222241110
 一个简单的todo应用程序
 要运行这个项目需要下载项目本地，要在计算机上安装 Django 才能运行此应用程序
 切换到克隆的目录并运行以下命令
 $ python manage.py makemigrations
 将创建运行此应用程序所需的所有迁移文件（数据库迁移
 $ python manage.py migrate
 我使用pycharm和anaconda管理，在conda上创建虚拟环境，在pycharm上file,settings,python interpreter上添加一个
 然后我们的 todo 应用程序将上线。我们需要创建一个 admin 用户来运行这个 App。在终端上，键入以下命令并提供 admin 用户的用户名、密码和电子邮件
 $ python manage.py createsuperuser
 需要暂时启动服务器，然后就可以开始使用我们简单的 todo App。按照命令启动服务器
 $ python manage.py runserver
 托管服务器后，前往 http://127.0.0.1:8000/todos 。