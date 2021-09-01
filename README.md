# Beijing-Bus-Network

This data is colleted from the Ministry of Transport of the People's Republic of China, and processed into an edge list which anyone can construct a network with it.
This data is based on the spreadsheet pubilished on Nov 2020. A processed file will also be added(in pyhton), it should work for new pubilished data as well(with the same format).

Please be aware that this network is simple, with the following properties:
* Undirected
* Unweighted
* No multi-links
* No self-links

The network has 9249 nodes and 14058 edges.

Format of the csv file: Contains two columns: source and target.

Original sources:
https://www.mot.gov.cn/sjkf/202005/t20200528_3333174.html
Viewed on 01/09/2021.
