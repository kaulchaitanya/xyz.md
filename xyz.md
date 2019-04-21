#include<iostream>
#include<string>
using namespace std;
class movie
{
    string title;
    int year;
    string name;
    public:
    void setTitle(string s)
    {
    title=s;
    }
    void setYear(int s)
    {
    year=s;
    }
    void setDirector(string s)
    {
    name=s;
    }
    void display()
    {
    cout<<"Title:"<<title<<"\n";
    cout<<"Year:"<<year<<"\n";
    cout<<"Name of Director:"<<name<<"\n";
    }
};
int main()
{
cout<<"Enter title year and name of director\n";
string s,t;
int a;
cin>>s;
cin>>a;
cin>>t;
movie obj;
obj.setTitle(s);
obj.setYear(a);
obj.setDirector(t);
obj.display();
return 0;
}

