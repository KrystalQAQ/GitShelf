**九识通用推送文档**

**V2.11**

<table><tr><td>日期</td><td>版本</td><td>说明</td><td>作者</td></tr><tr><td>2023/4/8</td><td>V1.0</td><td>新增文档</td><td>肖伟</td></tr><tr><td>2023/7/4</td><td>V2.0</td><td>增加刹车、油门等字段</td><td>肖伟</td></tr><tr><td>2023/7/9</td><td>V2.1</td><td>业务推送增加上一个停靠点id和name</td><td>肖伟</td></tr><tr><td>2024/8/25</td><td>V2.2</td><td>补充充电状态、车辆模式枚举值</td><td>李鹏飞</td></tr><tr><td>2024/10/8</td><td>v2.3</td><td>补充挡位,方向盘,转向灯等字段</td><td>范亚运</td></tr><tr><td>2024/10/15</td><td>v2.4</td><td>增加胎压</td><td>肖伟</td></tr><tr><td>2024/11/06</td><td>V2.5</td><td>车辆实时数据增加zoeStatus和zoeStatusName</td><td>倪文斌</td></tr><tr><td>2025/03/20</td><td>v2.6</td><td>车辆实时数据新增货箱状态</td><td>肖伟</td></tr><tr><td>2025/05/22</td><td>v2.7</td><td>实时数据新增dispatchId</td><td>李鹏飞</td></tr><tr><td>2025/07/10</td><td>v2.8</td><td>增加冷机温度,货箱温度推送</td><td>肖伟</td></tr><tr><td>2025/08/06</td><td>v2.9</td><td>增加距离下一个点位;增加预期时间和规划距离</td><td>肖伟</td></tr><tr><td>2025/08/26</td><td>v2.10</td><td>新增当前点位序号currentGoallIndex,当前路段序号currentPathIndex</td><td>李鹏飞</td></tr><tr><td>22025/11/20</td><td>v2.11</td><td>1.业务状态推送消息,补充cancelled: true/falsecancelReason:&quot;无法恢复任务&quot;;2.实时消息,补充车辆锁状态doors。</td><td>李鹏飞</td></tr></table>

**目录**

**目录**

1文档简介.. 4

1.1 特别声明. 4   
1.2 阅读对象. 4   
1.3 准备工作. 4

2无人车实时数据推送接口. 4  
3 无人车业务状态推送接口.. 9  
3 附录.. . 11

3.1车辆配送状态. . 11  
3.2 订单状态. . 12   
3.3 车辆模式. . 12  
3.4 充电状态. . 12   
3.5 档位状态. . 13   
3.6 车辆状态. . 13