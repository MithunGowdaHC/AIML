import matplotlib.pyplot as plt

left_coordinates = [1,2,3,4,5]
heights = [10,20,30,40,50]
bar_labels = ['one','two','three','four','five']
plt.bar(left_coordinates,heights,tick_label=bar_labels,width=0.6,color=['red','blue','green','yellow','orange'])
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title("A simple bar graph")
plt.show()
