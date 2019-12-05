#include<string>
#include<algorithm>
#include<vector>
#include<map>
using namespace std;

struct Photo {
    string name;
    string type;
    int time;
    int index;
};

bool cmp(Photo &a, Photo &b)
{
    if (a.type != b.type)
        return a.type < b.type;
    return a.time < b.time;
}

int main()
{ 
    vector<Photo> v;
    for (int i=0; i<v.size(); i++)
        //...
    
    sort(v.begin(), v.end(), cmp);
    //...
    
    map<int, Photo> m;  //int : (desired) Key, Photo : Value
    for (int i=0; i<v.size(); i++)
        m[v[i].time] = v[i];
    //...
    
    //O(1)
    int desiredTime = 20191210;
    Photo p = m[desiredTime];
}
