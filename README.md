# Показ возможностей Markdown
~~Несколько~~ 2 факта об о мне:
* Полтора года убучался в **Яндекс.Лицее**, не смог закончить убучение из-за низкой успеваемости
* Полгода прожил в Мексике
  
Привиду 2 цитаты:
1. Из *Сократа*
> Я знаю, что ничего не знаю
2. И из кода *Quaqe III Arena*
```C
float Q_rsqrt( float number ){
    long i;
    float x2, y;
    const float threehalfs = 1.5F;

    x2 = number * 0.5F;
    y  = number;
    i  = * ( long * ) &y;                       
    i  = 0x5f3759df - ( i >> 1 );               
    y  = * ( float * ) &i;
    y  = y * ( threehalfs - ( x2 * y * y ) );  
//  y  = y * ( threehalfs - ( x2 * y * y ) );   

    return y;
```

В качестве изображения приведу свою аватарку с **GitHub**

![Оригинал моей аватарки на github][avatar]


[avatar]: img/avatar.jpg