# HA-serverchan
Homeassistant custom component to push notify message to weixin. Please report bugs to dengleer#126.com

Server酱 introduction:   
http://sc.ftqq.com/3.version   

Serverchan.py is poorly coded but a working version.  
Before Homeassistant 0.92 copy serverchan.py under .homeassistant/custom_components/notify;
After 0.92 copy serverchan.py as .homeassistant/custom_components/serverchan/notify.py,prepare manifest.json accordingly. 

example  in configuration.yaml:   
notify:   
  \- name: weixin    
  
       platform: serverchan　　　　
       sc_key: xxxxxxxxxxxxxxxxxxxxxx   

Warn:"title" should NOT be null.
