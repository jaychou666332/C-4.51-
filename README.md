# C-4.51-
/*100匹马驼100担货，大马一匹驼3担，中马一匹驼2担，小马两匹驼1担。编写程序计算大，中，小马的数目*/
#include <stdio.h>
#include <stdlib.h>
main() {
	int x,y,z;
	for(x=0;x<=100;x++)
	   for(y=0;y<=100;y++)
	      for(z=0;z<=100;z++)
	      {if(z%2==0&&3*x+2*y+0.5*z==100)
	       printf("%d,%d,%d\n",x,y,z);
		  }
		  
}
