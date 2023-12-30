#include <bits/stdc++.h>
using namespace std;

int main(){
    vector<int> v;
    v.push_back(1);//will take 1 in the empty vector
    v.emplace_back(2);//will put 1,2 in the emply container
    vector<pair<int,int>>vec;
    vector<int>::iterator it=v.begin();//points to the memory like pointer like the value
    it++;//moves to the value of next memory
    cout<<*(it);
    vector<int>::iterator it=v.end();//right after end
    cout<<v[0]<<v.at(0);//0th value
    cout<<v.back();//last element
    for(vector<int>::iterator it=v.begin();it!=v.end();it++){
        cout<<*(it);
    }//to print a vector
    for(auto it:v){
        cout<<it;
    }//2nd way to print using auto assignation(you dont have to write the whole syntex)
    
    return 0;
}
