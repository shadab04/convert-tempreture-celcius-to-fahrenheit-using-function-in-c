# convert-tempreture-celcius-to-fahrenheit-using-function-in-c
#include<stdio.h>
float convertTemp(float k);
int main()
{
   float k=convertTemp(10);
    printf("calcios:\n%f",k);
    return 0;
}
float convertTemp(float c)
{
    float k=c+273.0;
    return k;
}
