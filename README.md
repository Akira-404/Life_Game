# Life_Game（生命游戏）

## 运行环境：`win10`，`vs2019`，`xeasy图形库`  

生命游戏是英国数学家约翰·何顿·康威在1970年发明的`细胞自动机`。
生命游戏其实是一个零玩家游戏，它包括一个二维矩形世界，这个世界中的每个方格居住着一个活着的或死了的细胞。  
一个细胞在下一个时刻生死取决于相邻八个方格中活着的或死了的细胞的数量。  

## 生命游戏规则：  
1.生命害怕孤独，如果一个生命周围的生命少于2个，生命就在下一个回合结束时死亡。  
2.生命讨厌拥挤，如果一个生命周围的生命超过3个，生命就在下一个回合结束时死亡。  
3.生命会繁殖，如果一个空位置周围有3个生命，它就在回合结束时获得生命。  
4.如果生命周围有2、3个生命，它在下一个回合结束时保持原样。  

##运行效果图：  
![Image text](http://github.com/omega-Lee/Life_Game/raw/master/game.jpg)
