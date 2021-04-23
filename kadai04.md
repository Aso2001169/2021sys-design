```uml
@startuml
start
:weather=天気情報;
if(weather=0) then ;
  :快晴です;
 elseif (weather=1) then;
 :曇りです;
 elseif (weather=2) then;
 :雨です;
 elseif (weather=???) then;
 :不明です;
 else
 end
 @enduml
```
 
