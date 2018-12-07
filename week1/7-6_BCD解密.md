# 7-6 BCD解密

```C
#include <stdio.h>
int main() {
    int num; scanf("%d", &num);
    if(num == 0)
        printf("0");
    else
        printf("%d%d", (num & 0xf0) >> 4, num & 0x0f);
    return 0;
}

```

或者

```C
#include <stdio.h>
int main() {
    int num; scanf("%d", &num);
	printf("%x", num);
    return 0;
}
```

