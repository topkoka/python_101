# Types of Operators

* Arithmetic 

``` +,-,*,/,% ```
```python
a = 5
b = 6
print(a+b) # 11
print(a-b)
print(a*b)
print(a/b)
print(a%b)

```
* Comparison 

``` <,>,<=,>= ```
```python
a=6
b=5
if a>5: 
    print('hi') 
elif a<5:
    print('low')   
```
* Logical    

``` and,or,not ```
```python
a=6
b=5
c= True
if a>5 and b>4:
    print('hi')
elif a<5 or b<6:
    print('low')   
print(not c) # !True = False
```
* Assignment

``` +=,-=,*=,/=,%= ```
```python
a = 5
b = 5

b += a #10
b -= a #5`
b *= a #25
b /= a #5.0
b %= a #0.0

```
* bitwise    

``` &,|,~,^,>>,<< ```

#### new python

* identity   

``` is , is not ```
compare the objects, same object,same memory location:
```
x = ["apple", "banana"]
y = ["apple", "banana"]
z = x

print(x is z) #True  
print(x is y) #False
print(x == y) #True

print(x is not z) #False
print(x is not y) #True

```

``` in , not in ```

```python
x = ["apple", "banana"]
#in
print("banana" in x) #True
print("pineapple" in x) #False
# not in
print("banana" not in x) #True
print("pineapple" not in x) #False
```
