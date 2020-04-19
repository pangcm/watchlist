"# watchlist" 

Flask入门教程的示例demo，源码的地址在[这里](https://github.com/greyli/watchlist)

# 安装部署方法
```bash
git clone https://github.com/greyli/watchlist.git
cd watchlist
python3 -m venv env  # 创建虚拟环境
. env/bin/activate  # 激活虚拟环境
pip install -r requirements.txt  # 安装所有依赖
flask initdb  # 初始化数据库
flask forge  #创建初始化测试数据
flask admin  # 创建管理员账户
flask run  #启动服务
```