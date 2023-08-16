a = [1,23,4,5,554,6456,867,9,100,456]

b = filter(lambda x: x % 2 == 0, a)

for x in b:
  print(x)
