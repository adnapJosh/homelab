# Setup  
[Dashy](https://dashy.to/) has a very easy setup process with Docker which they have on the website's [quick start](https://dashy.to/docs/quick-start) guide.  
```
docker run -d \
  -p 8080:8080 \
  -v ~/my-conf.yml:/app/user-data/conf.yml \
  --name my-dashboard \
  --restart=always \
  lissy93/dashy:latest
```  
After the intialization, the Dashy dashboard is accessed through `http://localhost:8080`  

I was able to put most of the services that have a web-gui through Dashy's interactive editor instead of the config file, which is a nice touch.  
![image](https://github.com/adnapJosh/homelab/assets/44041134/df03a449-7340-484d-8520-aa04c685a5b8)

Once I get more services up and running, I'm sure that my dashboard items will expand.

# Update 5/16/24
I've been trying to implement more monitoring widgets to my Dashy page, but I've run into some issues with trying to configure the Dashy conf.yml file.  
I can't seem to find the files in my linux VM where they should be.  
It may be because of my [Portainer](Portainer) install interacting with my Dashy install, but I need to learn more about both to track down the issue.  
