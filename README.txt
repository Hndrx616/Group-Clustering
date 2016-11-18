This is a method of supervised learning to take input and outputs of RSS and XML feeds from a list of blog sites to make predictions and generate a feed vector, hierarchial cluster lists, and visual dendrograms.

1. open a cmd window on the python_Lib folder
2. python setup.py install
3. open a cmd window on the bs4 folder
4. python setup.py install
5. python generatefeedvector.py
6. switch to python
7. >> import clusters
8. use the functions written in the code to generate outcomes i.e.
>> reload(clusters)
>> rdata=clusters.rotatematrix(data)
>> wordclus=clusters.hclusters(rdata)
>> clusters.drawdendrogram(wordclust,labels=words,jpeg='wordclust.jpg')