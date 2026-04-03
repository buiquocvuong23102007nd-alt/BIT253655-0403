# BIT253655-0403
def bai1():
r = float(input(" Nhap ban kinh tu ban phim:"))
Pi = 3.14
c = 2 * r * Pi
print(" Tong" ,c)
def bai2():
ds = []
for i in range(5):
    ten = input(f"Nhập tên người thứ {i+1}: ")
    ds.append(ten)
print("Danh sách ban đầu:", ds)
if len(ds) >= 2:
    ds.pop(1)
print("Danh sách sau khi xóa:", ds)
def bai4():
class Book:
    def __init__(self, name, price):
        self.__name = name
        self.__price = price
    def get_name(self):
        return self.__name
    def set_name(self, name):
        self.__name = name
    def get_price(self):
        return self.__price
    def set_price(self, price):
        self.__price = price
Book ("Covan": ,"self price")
