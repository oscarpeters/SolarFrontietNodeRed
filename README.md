# Solar Frontier Node-Red
### Solar Frontier data to Influxdb using Node Red

Tested on a `Solar Frontier Turbo 1P`

The Solar Frontier converter must have a ```Static IP-address``` to get this flow working properly. 

The whole Flow is made simple. There are a couple of things that have to be changed according to your own environment.
These are the `InfluxDB`, and the `Http request` node.



![Image of Flow](https://github.com/oscarpeters/SolarFrontietNodeRed/blob/main/pictures/main.PNG)

Change the `Http request` and `IP-ADDRESS` to your Solar Frontier IP-address.

The `Timestamp` is set to 10 seconds.

![Image of Flow](https://github.com/oscarpeters/SolarFrontietNodeRed/blob/main/pictures/change.PNG)

