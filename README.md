# 1. feladat
# homerseklet = int(input('Add meg a hőmérséklet értékét: '))
# print(homerseklet, '°C = ', homerseklet*1.8+32, "°F" )

#2. feladat
# a = float(input('Add meg egy téglalap egyik élét: '))
# b = float(input('Add meg egy téglalap másik élét: '))
# c = float(input('Add meg egy téglalap harmadik élét: '))

# if a > 0 and b > 0 and c > 0:
#     print('A téglatest felszíne: ', 2*(a*b+a*c+b*c), 'cm^2')
#     print('A téglatest térfogata: ', a*b*c, 'cm^3')

#3. feladat
# szam = int(input('Adj meg egy pozitív egész számot: '))

# db = 0
# for i in range(szam+1):
#     print(f'{i}', end =' ')
#     if i%10 == 7:
#         db+=1
# print('\nHéttel végződőek száma: ', db)

#4. feladat
# import random

# megengedett = int(input('Add meg a legnagyobb megengedett sebességet: '))

# sebesseg = random.randint(6000,13000)/100
# print('Sebességed: ',sebesseg)

# if sebesseg-megengedett < 20:
#     print('Nme kell büntetést fizetned!')
# elif sebesseg-megengedett >= 40:
#     print('50.000Ft-ot kell fizetned!')
# else:
#     print('30.000Ft-ot kell fizetned!')

#5. feladat
# import random

# osszeg = 0
# db = 0
# for i in range(10):
#     szam = random.randint(0,100)
#     if szam%3 == 0 and szam%4 != 0:
#         print(f'{szam}', end=',')
#         osszeg += szam
#         db += 1
# print('\nA számok átlaga: ', osszeg/db)

#6. feladat
# szam = int(input('Add meg, hogy hány sorból álljon az alakzat: '))

# for i in range(szam):
#     for j in range(0,i):
#         print(f'_', end = '')
#     print(f'0', end = ' ')
#     for j in range(i+1, szam):
#         print(f'_', end = '')
#     print('\n')





