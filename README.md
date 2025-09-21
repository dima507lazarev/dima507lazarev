#include <iostream>
#include <cmath>

using namespace std;

#define task4
#ifdef task1
int main(){
    //a
    cout << "2 кг" << endl;
    cout << "13 17" << endl;
    //b
    double a,b;
    cin >> a >> b;
    cout << a*1 << endl;
    cout << 19*b<< endl;
    //c
    double x,y;
    cin >> x >> y;
    cout << x*y << endl;
    cout << 5*y << endl;
    return 0;
}
#endif

#ifdef task2
int main(){
    //a
    double x;
    cin >> x;
    cout << 2*x << endl;
    //б
    double x1;
    cin >> x1;
    cout << sin(x1) << endl;
    //в
    double x2;
    cin >> x2;
    cout << x2*x2 << endl;
    //г
    double x3;
    cin >> x3;
    cout << sqrt(x3) << endl;
    //д
    double x4;
    cin >> x4;
    cout << abs(x4) << endl;
    //е
    double y;
    cin >> y;
    cout << 5*cos(y)<< endl;
    //ж
    double a;
    cin >> a;
    cout << -7.5*(a*a) << endl;
    //з
    double x5;
    cin >> x5;
    cout << 3*sqrt(x5) << endl;
    //и
    double alpha,beta;
    cin >> alpha >> beta;
    cout << sin(alpha)*cos(beta)+cos(alpha)*sin(beta) << endl;
    //к
    double a2,b;
    cin >> a2 >> b;
    cout << a*sqrt(2*b) << endl;
    //л
    double alpha1,beta1;
    cin >> alpha1 >> beta1;
    cout << 3*sin(2*alpha1)*cos(3*beta1) << endl;
    //м
    double x6,y1;
    cin >> x6 >> y1;
    cout << -5*sqrt(x6+sqrt(y1)) << endl;
    return 0;
  
}

#endif

#ifdef task3
int main(){
    //a
    double x;
    cin >> x;
    cout << -1/(x*x) << endl;
    //b
    double a,b,c;
    cin >> a >> b >> c;
    cout << a/(b*c) << endl;
    //B
    double a1,b1,c1;
    cin >> a1 >> b1 >> c1;
    cout << (a1/b1)*c1 <<endl;
    //g
    double a2,b2;
    cin >> a2 >> b2;
    cout << (a2+b2)/ 2 << endl;
    //d
    double a3,b3;
    cin >> a3 >> b3;
    cout << 5.45*(a*3+2*b*3/2-a*3) << endl;
    //e
    double a4,b4,c2;
    cin >> a4 >> b4 >> c2;
    cout << -b4+sqrt((b4*b4)-4*a*c)/a*2 << endl;
    //ж
    double a5,b5,c3;
    cin >> a5 >> b5 >> c3;
    cout << (-b5+1/a5)/(2/c3) << endl;
    //з
    double a6,b6;
    cin >> a6 >> b6;
    cout << 1/ 1+(a+b/2) << endl;
    //N
    cout << 1 / ( 1 + ( 1 / 2 + ( 1 / 2 + ( 3 / 5)))) << endl;
    //k
    double m,n;
    cin >> m >> n;
    cout << pow(2, pow(m,n)) << endl;
    return 0;
}
#endif

#ifdef task3
int main(){
    double a;
    cin >> a;
    cout << pow(a)+10/sqrt(pow(a)+1) << endl;
    return 0;
}
#endif
