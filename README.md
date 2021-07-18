# Level 5

Diberi suatu fungsi
```
def riddle(x,y):
    while (y != 0) :
        if ((x+y) % y != 0):
            print(y)
        else:
            print(x)
        y = y-1
        if (x%2 == 0):
            x = x+1
        else:
            x = x+x 
```
Berapa hasil penjumlahan dua output paling terakhir yang ditampilkan oleh fungsi riddle(1,15) ?


