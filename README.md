data1 = input("data1: ")
list1 = data1.split(",")
my_set = set(list1)
print("sorted set:", sorted(my_set))
element = input("element: ")
if element in  my_set:
  print("is",element,"in set:","True")
else:
  print("is",element,"in set:","False")
