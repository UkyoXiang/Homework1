#說明

今天寫程式的天氣..是雨天，真舒服。

#程式碼
```
#include <stdio.h>
#include <stdlib.h>
#include <math.h>
#define PI 3.1415926
int main() {
	float a, x, y, n;//先設定好
	for (n = 0; n < 5; n++){//開始N等於零到四迴圈
		a=n*2*PI/5;//設定N的值
		printf("x=%f,y=%f\n", cos(a), sin(a));//加入math的標頭檔使用函數
	}
	system("pause");
	return 0;	
}
```
#截圖
![Alt text](/456.jpg)

