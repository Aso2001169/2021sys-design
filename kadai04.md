```uml
@startuml
start
:weather=天気予報;
if(weather) then (0)
  :快晴です;
 else(1)
 :曇りです;
 else(2)
 :雨です;
 else (その他)
 :不明です;
 elseif
 end
 @enduml
```
 
