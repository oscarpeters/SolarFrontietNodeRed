# SolarFrontietNodeRed
Solar Frontier data to Influxdb using Node Red

The Solar Frontier converter must have a static IP-address to get this working properly. 

The hole Flow is made simple. The things that are needed to be changed are the `InfluxDB`, and the `Http request` node
![Image of Flow](https://github.com/oscarpeters/SolarFrontietNodeRed/blob/main/pictures/main.PNG)

Change the `Http request` and change `IP-ADDRESS` to your Solar Frontier IP-address.

The `Timestamp` is set to 10 seconds.

![Image of Flow](https://github.com/oscarpeters/SolarFrontietNodeRed/blob/main/pictures/change.PNG)

