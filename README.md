**Goal: To find out the rotating angle from player to shrine**
## Input
![image](https://github.com/a-tien/filter/assets/87262409/d1f4d76d-3079-4962-94bd-cb5017e15cfa)

## Output
![image](https://github.com/a-tien/filter/assets/87262409/a3d49605-ba3a-4489-8ae3-7c49860e3681)


# CV2 function in this project
cv2.inRange() -> 只擷取想要的顏色區間
![image](https://github.com/a-tien/filter/assets/87262409/ab15cb56-bfb1-416f-b3f6-b3926aea3a29)
cv2.findContours()跟cv2.moment()結合取得質心的x,y座標
cv2.minEnclosingTriangle()中可以取得頂點以便這次去計算距離跟向量來找到玩家的方向
cv2.line()在質心之間畫線
