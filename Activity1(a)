#include<iostream>
#include<string>
using namespace std;

class stu{
    public:
    char name[30],add[30];
    int roll,zip;

    stu();
    ~stu();
    void read();
    void display();
};
stu::stu()
{
    cout<<"\nThis is Student Details constructor called  ............"<<endl;
}
void stu::read()
{
    cout<<"\nEnter the student Name : ";
    cin>>name;
    cout<<"\nEnter the student roll no : ";
    cin>>roll;
    cout<<"\nEnter the student address: ";
    cin>>add;
    cout<<"\nEnter the Zipcode :";
    cin>>zip;
}
void stu::display()
{
    cout<<"\nThe Entered Student Details are shown below :.............\n";
    cout<<"\nStudent Name : "<<name<<endl;
    cout<<"\nRoll no is : "<<roll<<endl;
    cout<<"\nAddress is : "<<add<<endl;
    cout<<"\nZipcode is :"<<zip;
}
stu:: ~stu()
{
    cout<<"\n\nStudent Details is Closed...............\n";
}
int main()
{
    stu s;
    s.read();
    s.display();

    return 0;
}
