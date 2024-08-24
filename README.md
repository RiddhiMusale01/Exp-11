# EXPERIMENT 11
# Aim 
To Study and Implement Classes and Objects
# Software 
Visual Studio Code
# Theory
CODES:

1.
```
#include <iostream>
using namespace std;
class cube{
    public:
    double height=3.4;
    double length=9.2;
    double width=4.1;

};
int main(){
    cube c1;
    double volume=c1.height*c1.length*c1.width;
    cout<<"Volume:"<<volume<<endl;
    
}
```

O/P:

![image](https://github.com/user-attachments/assets/ef7136d1-39a5-4a52-aa18-cbb2dcda6159)

2.
```
#include <iostream>
using namespace std;
class cube{
    public:
     double height=3.4;
    double length=9.2;
    double width=4.1;
    double volume(){
        double v;
        v=height*width*length;
        return v;
    }
};
int main(){
    cube c1;
    cout<<"Volume:"<<c1.volume()<<endl;
}
```

O/P:

![image](https://github.com/user-attachments/assets/e74d4f0f-914c-48e0-b049-7852ac10590a)

3.
```
#include<iostream>
using namespace std;
class cube{
    private:
    double height=3.4;
    double length=9.2;
    double width=4.1;
    public:
    double volume()
    {
        double v;
        v=height*length*width;
        return v;
    }
};
int main()
{
    cube c1;
    cout<<"Volume:"<<c1.volume()<<endl;
}
```

O/P:

![image](https://github.com/user-attachments/assets/9fcc38ce-dbc6-4c1a-9915-2a48c34c1a42)

4.
```
#include <iostream>
using namespace std;
class cube{
    public:
    double height=3.4;
    double length=9.2;
    double width=4.1;
     double volume(){
     double v;
     v=height*width*length;
        return v;
}
void disp_vol(double vol){
    cout<<"Volume:"<<vol<<endl;

}
};
int main()
{
    cube cube1;
    double vol=cube1.volume();
    cube1.disp_vol(vol);
}
```

O/P:

![image](https://github.com/user-attachments/assets/abd1c7f9-90d4-4760-92e0-e61606347653)

5.
```
#include <iostream>
using namespace std;

class Volume 
{
    public:
        float length;
        float breadth;
        float height;
        
        void input() {
            cout << "Enter the value of length: ";
            cin >> length;
            cout << "Enter the value of breadth: ";
            cin >> breadth;
            cout << "Enter the value of height: ";
            cin >> height;
        }
                float vol() {
            return length * breadth * height;
        }
        
        void display() {
            double a = vol();
            cout << "The volume is " << a;
        }
};

int main() {
    Volume volume1;
    volume1.input();
    float a = volume1.vol();
    cout << a;
    return 0;
}
```

O/P:

![image](https://github.com/user-attachments/assets/288a79cb-ab5e-4413-9f94-706a2e6cebd8)

# Conclusion
