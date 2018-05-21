# SignalR Web Socket Connection - Issue on Clustering

## Error
WebSocket connection to 'wss://underworld.loki.com/common/real-time/common?id=6Z_0Zf7SmkWIQrazwJHPmg' failed: Error during WebSocket handshake: Unexpected response code: 404

## Test Application
* Open `index.html`
* Press `Connect`
* Notes: You need to press connect around 1 to 15 times to be able to connect successfully.

## Currently we are using:
* Signalr Javascript client : `1.0.0-rc1-update1`
* Server-Side NuGet Packages: `1.0.0-rc1-final`
* Signalr Server is running on Kubernetes cluster of: `4 instances`
* Kubernetes: using `ingress with ngnix`
* Operating System on the Server: `Linux`
* Operating System on the Client: `Windows`
* Host: `AWS`
* Browser on the client: `Chrome`

## Need Additional Info
If you need additional info do not hesitate to contact me.


This sample was copied from [Signalr Official Samples](https://github.com/aspnet/SignalR/blob/dev/samples/SignalRSamples/wwwroot/streaming.html)

## Error Screenshot
 ![client-logs](./client-trace-error.jpg)