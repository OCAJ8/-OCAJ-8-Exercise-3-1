# OCAJ-8-Exercise-3-1

|Assigned Value of a|Compound Assignment|Refactored Statement|New Value of a|
|---|---|---|---|
|a = 10;|a += 3;|a = 10 + 3;|13|
|a = 15;|a -= 3;|a = 15 - 3;|12|
|a = 20;|a *= 3;|a = 20 * 3;|60|
|a = 25;|a /= 3;|a = 25 / 3|8|
|a = 30;|a %= 3;|a = 30 % 3|0|
|a = 35;|a &= 3;|a = 35 & 3 which is bitwise AND: (0010 0011) & (0000 0011)|(0000 0011) == 3|
|a = 40;|a ^= 3;|a = 40 ^ 3 which is XOR: (0010 1000) ^ (0000 0011)|(0010 1011) == 43|
|a = 45;|a \|= 3;|a = 45 \| 3 which is bitwise OR: (0010 1101) ^ (0000 0011)|(0010 1111) == 47|
|a = 50;|a <<= 3;|a = 50 << 3 which is Binary Left Shift Operator: (0011 0010)|(011 0001 0000) == ???? **wasn't able to figure this one out**|
|a = 55;|a >>= 3;|a = 55 >> 3 which is Binary Right Shift Operator: (0011 0111)|(0000 0110) == 6 |
|a = 60;|a >>>= 3;|a = 60 >>> 3 which is Shift right zero fill Operator: (0011 1100)|(0000 0111) == 7 |
