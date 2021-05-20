# streams
 This app to practise on react redux, redux-thunk redux-form, react-router and sample REST server 
 
 In this app we will create, edit, delete streams with above mentioned react and redux libraries. If OBS streamsing video is configured with any stream videos you are able to watch that video in Stream show component. 


# api
this folder is to act as server to work with JSON data. In this tiny project we used json-server npm.
you can observe that we configure the api server to run on 3001 port in local machine. we are connect from streams app to this api. You can find this configuration in Streams.js in api folder of streams app.


# rtmpserver
To work with this server we need to setup a OBS studio app in your machine(where rtmpserver running as we configured to get local streamin data)
in rtmpserver we are using NodeMediaServer configured with required basic details. You can find more details fron npm


This is some Udemy instructor project but explored all the code details with trail and error manner.