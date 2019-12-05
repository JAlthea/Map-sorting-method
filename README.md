# Map sorting method by vector
Simply, you can use vector(list) for sorting map, </br>
including basic sorting of map such as less(descending order) and greater(ascending order). </br>
This method is useful to custom-data-type such as class and struct.

# Purpose
For searching specific data by sorting of map which has non-default data type. </br>
O(n) -> O(1) </br></br>


To summarize process, 'vector -> sort -> (sorted)vector -> map'

```
vector<int, Photo> v;
...
sort(v.begin(), v.end(), cmp);
... 
map<int, Photo> m(v.begin(), v.end());
...
return m[desiredItem];
```
