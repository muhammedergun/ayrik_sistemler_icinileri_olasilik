

```python
#{1,2,3,4,...,24} kümesinden herhangi 13 eleman seçildiğinde bu seçilen elemanların içinde toplamı 25 olan en az 1 tane sayı ikilisinin bulunduğunu ispatlayınız.


import random
lst=[]
for i in range(1,25):
    lst.append(i)
print(lst)

liste=[]

for i in range(0,13):     
    for k in range(0,13):
        a=random.choice(lst)
        if(a  not in liste):
            liste.append(a)
            break
        else:
            continue           
print("secilen sayilar = %s"% liste)
                
for i in range(0,13):
    for x in range(0,13):
        if(liste[i]+liste[x]==25):
            print("%s + % s = 25 " %(liste[i],liste[x]))
            
```

    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
    secilen sayilar = [20, 6, 10, 12, 3, 1, 17, 23, 13, 4, 7, 15, 14]
    10 + 15 = 25 
    12 + 13 = 25 
    13 + 12 = 25 
    15 + 10 = 25 
    


```python

```


```python

```


```python

```


```python

```


```python

```
