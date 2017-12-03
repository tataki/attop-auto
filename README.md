# Attop-Auto
一个python实现的至善网刷课软件,主要是理解到了dwr框架下数据的交互
## Environment
> python 版本:3.6
> 系统: mac os

## Usage
    通过`http://www.attop.com/wk/learn.htm?id=48`获得起始和结尾jid
    
    ```
    列如:
    http://www.attop.com/wk/learn.htm?id=48&jid=993
    其中993为起点
    http://www.attop.com/wk/learn.htm?id=48&jid=1013
    1013为终点

    (看不懂就算了,写文档好累😫)
    ```
    将数值对应填入

    ``` python app.py -u (账号) -p (密码) -s (开始id,列如993) -e (结束id,列如1013) -m (模式)
    ('-u', '--username', help='attop username', default='')
    ('-p', '--password', help='attop password', default='')
    ('-s', '--start', help='start page', default=0)
    ('-e', '--end', help='end page', default=0)
    ('-m', '--mode', help='1为刷评价,2为刷学习时长,3为刷题,默认全刷', default=0)
    ```

## Task
- [ ] 任务一  `自动获取网站页数`
- [ ] 任务一  `更新题库功能`


## Attention 
1.  视频时间每次必须间隔为15s
2.  课程评价时间不可短于3S
3.  刷题功能不保证最新提供,请更新题库后再使用
4.  获得题库的js文件已送上~

欢迎pr
