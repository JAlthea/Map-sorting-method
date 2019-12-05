Simply, you can use vector(list) for sorting map, 
including basic sorting of map such as less(descending order) and greater(ascending order).
This method is useful to custom-data-type such as class and struct.


To summarize the code, 'vector -> sort -> (sorted)vector -> map'

'''
vector<int, Photo> v;
...
sort(v.begin(), v.end(), cmp);
... 
map<int, Photo> m(v.begin(), v.end());
...
'''
