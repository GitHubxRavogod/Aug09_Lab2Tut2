# Aug09_Lab2Tut2

import matplotlib.pyplot as plt
fig = plt.figure(figsize=(10,8))    # width x height in inches
ax1 = fig.add_subplot(111)     
gradeFeq = {'A':1,'B':2,'C':3,'D':2,'F':1}
ax1.bar(['A','B','C','D','F'],
	[gradeFeq['A'],gradeFeq['B'],gradeFeq['C'],gradeFeq['D'],gradeFeq['F']])
ax1.set_xlabel('Grade')
ax1.set_ylabel('Student Numbers')
ax1.set_title('Grade Distribution')
plt.show()

# print "1997" in binary 
print(bin(1997))
# print "1011100100" in decimal
print(int('1011100100', 2))
# print "1011100100" in hexadecimal
print(hex(740))
