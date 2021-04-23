```uml
@startuml
start
:weather=天気予報;
if(weather) then (0)
  :快晴です;
 else(1)
 :曇りです;
 elseif(2)
 :雨です;
 elseif(その他)
 :不明です;
 elseif
 end
 @enduml
```
 
