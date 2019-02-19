# drawing-book
#include <assert.h>
#include <limits.h>
#include <math.h>
#include <stdbool.h>
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
main()
{
long long int n,p,i;
scanf("%lld %lld",&n,&p);
if(p<=(n-p))
    {
        printf("%lld",p/2);
    }
else if(p>(n-p))
    {if(n-p==1)
        printf("1");
    else
        printf("%lld",(n-p)/2);
    }
}
