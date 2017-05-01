# OCAJ-8-Exercise-3-1

|Assigned Value of a|Compound Assignment|Refactored Statement|New Value of a|
|---|---|---|---|
|a = 10;|a += 3;|a = 10 + 3;|13|
|a = 15;|a -= 3;|a = 15 - 3;|12|
|a = 20;|a *= 3;|a = 20 * 3;|60|
|a = 25;|a /= 3;|a = 25 / 3|8|
|a = 30;|a %= 3;|a = 30 % 3|0|
|a = 35;|a &= 3;|a = 35 & 3 which is bitwise AND: (11 110) & (00 011)|(00 010) or 2|
|a = 40;|a ^= 3;|a = 40 ^ 3 which is XOR: (101 000) ^ (000 011)|(101 011) or 43|
|a = 45;|a |= 3;|a = 45 | 3 which is bitwise OR: (101 101) ^ (000 011)|(101 111) or 47|
|a = 50;|a <<= 3;|a = 50 << 3 which is Binary Left Shift Operator: (110 010)|(010 000) or 16|
|a = 55;|a >>= 3;|a = 55 >> 3 which is Binary Right Shift Operator: (110 111)|(000 110) or 5|
|a = 60;|a >>>= 3;|a = 60 >>> 3 which is Binary Right Shift Operator: (111 100)|(000 111) or 7|
