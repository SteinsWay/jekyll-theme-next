基于交通大数据和个人行为习惯的智能出行决策系统和预警方案
研究背景
当今社会，随着人口数量的增多，以及城市化的发展，越来越堵的人口向大城市聚集，给世界上的众多大城市造成很大的交通压力。同时，社会的发展给人们提供了更多的物质服务，让城市人口配备了更多的交通工具，诸如汽车，自行车，摩托车等。而人们的出行需求也更加丰富。毫无疑问，地铁和公交车仍然是人们工作生活需要的首选。但是如果面对上下班高峰期或是重要活动的时候，其中的巨大交通压力也不小。可以预知，在2020年东京奥运会的时候，其交通拥堵和地铁使用量一定是非常巨大的。最重要的是，大型城市的人口聚集速度无论是如今还是未来，都会远远大于城市交通设备的更新速度，所以个性化的出行决策方案在如今显得尤为重要。如果能根据以往数据和人工智能预知特定交通/地铁的拥堵状况，再结合个人出行需求以及生活习惯提出合理的出行决策。既能够缓解重要交通的拥堵状况，又能够针对个人需求提出合理的出行安排，同时还能为个人旅游/上班学习出行，自动车导航，配送公司，交通系统给出合理的参考意见
先行研究
关于出行决策系统方面的研究很多，广泛采用的方法原型是运筹学方面的知识，通过设立影响因子（如天气，道路状况，日期，出行工具等），给各个影响因子赋权（平均赋权，层次分析赋权等各种赋权方法），来建立数学模型，在通过最小二乘法，图论中的相关知识（诸如旅行商问题）等，来计算出最优的时间空间上的出行方案。
而随着计算机和工业上的发展，诸如GIS，各大企业服务软件的提供，如：googleMap、乗り換え,高德地图等等的引用和厂商之间的数据共享，为现代的出行安排提供了大量的实时交通数据和利用工具。
在计算机上算法上，Djkstra算法，蚁群算法，遗传算法等算法的利用和优化，为实现方案，将原理变成现实提供了有力可靠的工具。
毫无疑问，信息时代已经为人们的出行提供了很大的便利。而如今，随着人工智能，机械学习，lifelog，大数据等技术的不断发展，我们可以或许可以享有更精确更人性化的出行决策。如果你在使用GOOGLE地图或是乗り換え等软件的时候，总是会因为步行或驾驶时间的误差而耽误约会时间，或是为了不那么急切的旅游计划（如演唱会，大型活动等）而在拥挤的地铁里挤的一身狼狈，或许我们可以同时考虑一个更加以个人目的和行为习惯为导向的智能出行方案
研究目的 计划
通过手机的log数据记录用户的步行习惯，将出行速度按照区间划分为两种日常交通工具（步行，自行车），同时计算并记录用户平均步行速度。做为一个影响因子。（同时如果针对的是拥有驾车习惯或外卖之类灵活性的用户，或许可以划分人群，针对性加入数学模型）
诸如上班高峰期，大型活动等的交通预警。如果你家住在国分寺，而你上班的地方在庆应大学三田附近，或许您有多种交通地铁换乘路径，比如最近的车站是赤羽桥，你也可以到达田町后步行过去，或许你也可以先到达神谷町。比如Floyd算法中最短路径问题，通过给有向图配置权重来计算最短路径。而在构建新的数学模型过程中，以起始点和目的地中的路径作为基础，以道路/地铁拥堵率（可能的出行人数/容量），（结合日期，出行状况等变量）来设置权重，同时给出行提前反馈拥堵信息，为人们出行提出更加轻松的参考选项。
以运筹学方法，将用户人群（对应不同交通工具和用户习惯），拥堵状况，危险指数等，结合人工智能，给出出行方案的推荐。
数据收集和代码实现
参考文献
大規模ユーザの時空間滞在・経路パターンに基づく 早期目的地予測
携帯電話から得られる大規模な位置履歴情報を用いた 都市動態モデリング
バス運行状況ウェブサービス情報を用いた 乗換案内アプリのための路線バス所要時間推定
The Using of Internet and WAP Technology for Publishing Traffic Information of Urban Road Network
Neural network implementation of the shortest path algorithm for traffic routing in communication networks
