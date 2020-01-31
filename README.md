numbs = [2, 5, 8, 4, 3, 6, 7, 9] 
first = numbs[0]
total = 0
for i in numbs:
	for j in numbs:
		x = i * j
		total += x
print (total)
