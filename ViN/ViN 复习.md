# ViN 复习

## Dynamic Routing Protocols

- The **forwarding function** directs every packet from an input port to the right output port, based on the header of the packet and the routing table(RT) 
- 转发功能将来自输入端口的每个包基于数据包头和路由表定向到右侧输出端口，

- The **routing function** exchanges reachability and topological information, computes the best route to any destination and populate the routing table accordingly.
- 路由功能交换可达性和拓扑信息，计算到达任何目的地的最佳路由并填充该路由表相应地。



动态路由的特点：

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135122551.png" alt="image-20230606135122551" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135139279.png" alt="image-20230606135139279" style="zoom:50%;" />

Distance Vector：存邻居的信息，每次传输都只和邻居进行

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135202493.png" alt="image-20230606135202493" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135216830.png" alt="image-20230606135216830" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135232120.png" alt="image-20230606135232120" style="zoom:45%;" />

有自适应性

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135445799.png" alt="image-20230606135445799" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135506148.png" alt="image-20230606135506148" style="zoom:50%;" />

link state：存全局的topology，根据topo算最短的RT

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135731280.png" alt="image-20230606135731280" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606135928027.png" alt="image-20230606135928027" style="zoom:50%;" />



RIP (Routing Information Protocol)<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606140057098.png" alt="image-20230606140057098" style="zoom:50%;" />

OSPF (Open Shortest Path First)<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606140237140.png" alt="image-20230606140237140" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606140301919.png" alt="image-20230606140301919" style="zoom:50%;" />

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606141119294.png" alt="image-20230606141119294" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606141141253.png" alt="image-20230606141141253" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606141237688.png" alt="image-20230606141237688" style="zoom:50%;" />

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606141256748.png" alt="image-20230606141256748" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606141345240.png" alt="image-20230606141345240" style="zoom:67%;" />



NAT

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606154736831.png" alt="image-20230606154736831" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606154834678.png" alt="image-20230606154834678" style="zoom:50%;" />

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606154923330.png" alt="image-20230606154923330" style="zoom:50%;" />



VPN：<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606155136359.png" alt="image-20230606155136359" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606155316478.png" alt="image-20230606155316478" style="zoom:50%;" />

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606155350098.png" alt="image-20230606155350098" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606155442673.png" alt="image-20230606155442673" style="zoom:50%;" />





## Traffic Engineering - Part 1. on IGP Administrative Weights

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606164822076.png" alt="image-20230606164822076" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606164903854.png" alt="image-20230606164903854" style="zoom:50%;" /><img src="/Users/suizhi/Library/Application%20Support/typora-user-images/image-20230606165202012.png" alt="image-20230606165202012" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606164934077.png" alt="image-20230606164934077" style="zoom:50%;" />



IGP Administrative Weights

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172016823.png" alt="image-20230606172016823" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172053264.png" alt="image-20230606172053264" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172120959.png" alt="image-20230606172120959" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172142117.png" alt="image-20230606172142117" style="zoom:50%;" />

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172200087.png" alt="image-20230606172200087" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172221193.png" alt="image-20230606172221193" style="zoom:50%;" />

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172254228.png" alt="image-20230606172254228" style="zoom:50%;" /><img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172305728.png" alt="image-20230606172305728" style="zoom:50%;" />

<img src="https://raw.githubusercontent.com/JeanDiable/MyGallery/main/img/image-20230606172322829.png" alt="image-20230606172322829" style="zoom:50%;" />

