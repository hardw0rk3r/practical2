converter.h
#ifndef converter_H
#define converter_H

class Converter
{
public:
    void hexToBigIndian(char hex, charbigIndian);
    void hexToLittleIndian(char* hex, char* littleIndian);
    void bigIndianToHex(char* hex, char* bigIndian);
    void littleIndianToHex(char* hex, char* littleIndian);
};
#endif
converter.cpp
#include <iostream>
#include "converter.h"

void Converter::hexToBigIndian(char * hex, char * bigIndian)
{
    for (int i = 0; i < 4; i++)
    {
        bigIndian[i] = hex[i];
        std::cout << bigIndian[i];
    }
}
void Converter::hexToLittleIndian(char* hex, char* littleIndian)
{
    int j = 3;
    for (int i = 0; i < 4; i++)
    {
        littleIndian[i] = hex[j];
        j++;
        i++;
        littleIndian[i] = hex[j];
        j = j - 3;
    }

}
void Converter::bigIndianToHex(char* hex, char* bigIndian)
{
    for (int i = 0; i < 4; i++)
    {
        hex[i] = bigIndian[i];
    }
}
void Converter::littleIndianToHex(char* hex, char* littleIndian)
{
    int j = 3;
    for (int i = 0; i < 4; i++)
    {
        hex [i] = littleIndian[j];
        j++;
        i++;
        hex [i] = littleIndian[j];
        j = j - 3;
    }


}
