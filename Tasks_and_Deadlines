#include<bits/stdc++.h>
using namespace std ;

int main(){

    int task_no ;
    cin>> task_no ;
    long reward = 0 ;
    long current_time = 0 ;
    vector<pair<int,int>>tasks ;

    for(int i=0 ;i<task_no ;i++){
        int duration , deadline ;
        cin>>duration>>deadline ;
        tasks.push_back({duration,deadline});
    }

    sort(tasks.begin(),tasks.end());

    for(auto task : tasks){
        current_time +=task.first ;
        reward += (task.second - current_time);
    }

    cout<<reward<<endl ;

    
}