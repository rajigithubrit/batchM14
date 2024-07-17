

# constructor
'print(str())'
# type casting

i, f, c, b =  str(43),str(4.3),str(3+4),str(6-4)
print(type(i),i)
print(type(f),f)
print(type(c),c)
print(type(b),b)
# .endswith

str1 = input("enter : \n")
sub_s = input("substring : \n")
print(str1.endswith (sub_s))
sub_s = input("substring :")
end_value = int(input("end-index : "))
print(str1.endswith (sub_s, 0, end_value))
