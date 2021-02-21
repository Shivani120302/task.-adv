#include<iostream>
using namespace std;
class time1
{
  public:
    void timeinsec(int hours,int min,int sec)
    {
      int secs;
      secs=(hours*60*60)+(min*60)+(sec);
      cout <<endl<< endl<<"the time in seconds : "<<secs <<endl;
      
    }
};
int main()
{
  int hours,min,sec;
  time1 t;
  cout<<" hours.?  ";
  cin >>hours;
  cout<<"  minutes.?  ";
  cin >>min;
  cout<<"  seconds.?  ";
  cin >>sec;
  t.timeinsec(hours,min,sec);
  return 0;
  
  
}
