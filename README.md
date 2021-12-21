# my-code-cheat-sheet
cheat sheet

**pandas**

data = pd.read_csv('file location')   _code to read a file_
data.head() _**code to read the first 5rows of the file_**
data.loc[:,[name of columns]]
data.sample(5) **this gives random 5 rows out of the file**
data.describe() **gives info on the data**
data.dropna() **deducts the null value rows in the column**
data.info() **give the number and type of characters in the data**


**numpy**

np.arange
np.sin
np.pi
np.linspace (**mainly used to create gid interval changes**)

**matplotlib.pyplot**

plt.plot(x,y, color = 'r' #red, linestyle = ':', linewidth = #number)
plt.title
plt.xlabel('Name', fontsize= '', family = 'Monospace')
plt.ylabel('Name', fontsize= '', family = 'Monospace')
plt.grid()
plt.xticks (dataset used, naming each grid line) #**this is to notify the intervals of gridlines**
plt.legend(['Sine','Cosine']) #**the legends should be in the form lists**
plt.hist(y, 15) #**this means to create a histogram with y data and use 15 bins**
plt.figure(figsize= [8,12]) #**this is to adjust the size of the figure as a whole to 8 in x axis and 12 in y axis**
plt.scatter(x, y , alpha = 0.2, marker ='x', s= 50) #**this is to create scatter plot with transparency of 0.2, the marker is the shape of plot points and s is the size of the markers**
plt.subplot(2,2,1) #**used to create multiple plots in a figure**
plt.semilogy(y,y**2) #to create a plot with log scale on the y axis
plt.text(4,0,'Some Text',fontsize = 20,backgroundcolor = 'red',color = 'blue') # this code is to create a text in the middle of a plot at x=4 and y=0
plt.pie([greater,lessthan],labels=['Greater','Less Than']);  ** this code is to create pie charts with labels on each sections as given names**


**Data retrievals**

make sure all data retrieval codes have a list bracket to it for it to work. i.e []

