# Beijing-Bus-Network

This data is colleted from the Ministry of Transport of the People's Republic of China, and processed into an edge list which anyone can construct a network with it.
This data is based on the spreadsheet pubilished on Nov 2020. A processed file will also be added(in pyhton), it should work for new pubilished data as well(with the same format).

Please be aware that this network is simple, with the following properties:
* Undirected
* Unweighted
* No multi-links
* No self-links

The network has 9249 nodes and 14058 edges.

Format of the network file(in csv): Contains two columns: source and target.

Format of the original xlsx and translation:
* 线路名称 - Route name
* 方向 - Direction
* 站点序号 - Stop ID
* 站点名称 - Stop name

Original sources:
https://www.mot.gov.cn/sjkf/202005/t20200528_3333174.html
Visited at 01/09/2021.

A preview of the network using Gephi:
![Preview](./Preview.png)
