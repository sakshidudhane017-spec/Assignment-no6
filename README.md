# Assignment-no6
Assignment no6
Open In Colab

a = [10, 20, 30, 40]

print("List:", a)

print(20 in a)
print(50 not in a)
     
List: [10, 20, 30, 40]
True
True

a = [1, 2, 3]
b = [4, 5]

c = a + b
print(c)

print(a * 2)

print(len(a))
print(max(a))
print(min(a))
     
[1, 2, 3, 4, 5]
[1, 2, 3, 1, 2, 3]
3
3
1

a = [10, 20, 30, 40, 50]

print(a[0])      # first element
print(a[-1])     # last element
print(a[1:4])    # slicing
     
10
50
[20, 30, 40]

a = [1, 2, 3, 4]

a[1] = 20
print(a)

a.append(5)
print(a)

a.insert(1, 100)
print(a)

a.remove(20)
print(a)
     
[1, 20, 3, 4]
[1, 20, 3, 4, 5]
[1, 100, 20, 3, 4, 5]
[1, 100, 3, 4, 5]
