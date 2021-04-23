```uml
@startuml
start
:weather=天気予報;
if(weather) then (0)
  :快晴です;
 else then (1)
 :曇りです;
 else then (2)
 :雨です;
 else then (その他)
 :不明です;
 elseif
 end
 @enduml
```
 
