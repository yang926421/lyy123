# lyy123
这是存储
list2 = [[7795, 100],[7895, 96],[7795, 98],[7795, 95]]
length = len(list2)
print(length)
for i in range(0,length):
    print(i)
for i in range(len(list2)-1):
    for j in range(len(list2)-1):
        if list2[j][1] > list2[j+1][1]:
            list2[j+1],list2[j] = list2[j],list2[j+1]
print(list2)
