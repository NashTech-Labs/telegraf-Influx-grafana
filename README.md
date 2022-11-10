# telegraf-Influx-grafana
this template will help you to gathers metrics about disk usage. store the metrices in influxdb and we can monitor those metrices through Grafana
Install docker
Clone Repositry and open power shell or cmd.
use docker-compose up 
4)Open respective ports where Grafana run in my case 192.**..10:3000
5)Add data souces influx with 192.**..10:8086 with default username and password as in configuration
6)You will be able to see metric in grafana
![grafana](https://user-images.githubusercontent.com/76486190/201180368-e3e1ee16-1b41-49ba-a508-755e0dd79ad0.png)

