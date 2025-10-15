# hello.py 
print("Hello, World!") 

# Deklarasi variabel 
x = 10           # Integer 
y = 3.14         # Float 
nama = "Alice"   # String 
print(x, y, nama) 

a = 5 
b = 2 
print(a + b)  # Penjumlahan 
print(a - b)  # Pengurangan 
print(a * b)  # Perkalian 
print(a / b)  # Pembagian 
print(a ** b) # Perpangkatan


# Loooping For 
for i in range(5): 
    print(i) 
 
my_list = [1, 2, 3, 4, 5] 
for elemen in my_list: 
    print(elemen) 


def salam(nama):  
    print("Hello, " + nama) 
 
salam("Alice") 
salam("Bob") 

my_list = [1, 2, 3, 4, 5] 
print(my_list) 
print(my_list[0])  # Akses elemen pertama 
my_list.append(6)  # Menambahkan elemen ke akhir list 
print(my_list) 

my_tuple = (1, 2, 3, 4, 5) 
print(my_tuple) 
print(my_tuple[0])  # Akses elemen pertama

my_dict = {"name": "Alice", "age": 25} 
print(my_dict) 
print(my_dict["name"])  # Akses nilai dengan kunci 
my_dict["age"] = 26     # Mengubah nilai 
print(my_dict)

# Set: Set adalah kumpulan elemen unik yang tidak terurut. 
my_set = {1, 2, 3, 4, 5} 
print(my_set) 
my_set.add(6)  # Menambahkan elemen 
print(my_set)
