# HA-serverchan
Homeassistant custom component to push notify message to weixin. Please report bugs to dengleer#126.com

Server酱 introduction:   
http://sc.ftqq.com/3.version   

Serverchan.py is poorly coded but a working version.  
Copy serverchan.py under .homeassistant/custom_components/notify. 

example  in configuration.yaml:   
notify:   
  \- name: weixin    
  
       platform: serverchan　　　　
       sc_key: xxxxxxxxxxxxxxxxxxxxxx   

Warn:"title" should NOT be null.
