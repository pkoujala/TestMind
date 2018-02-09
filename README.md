# TestMind
for testing changes

#include<iostream>
using namespace std;
  
class base
{
   public:
          virtual void show()
          {
             cout<<"base is called"<<endl;
          }
};

class dervived : public base
{
     public:
            void show()
            {
               cout<<"derived class is called"<<endl;
            }
};

int main()
{
   base *ptr;
   derived obj;
   ptr=&obj;
   ptr->show();
   
   return 0;
 }
  
