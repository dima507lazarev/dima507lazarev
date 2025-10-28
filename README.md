////////////////////////////
Дз за 21 сентября
////////////////////////////
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

#ifdef task4
int main(){
    double a;
    cin >> a;
    cout << pow(a,2)+10/sqrt(pow(a,2)+1) << endl;
    return 0;
}
#endif
////////////////////////////
 |
 |
\ /
////////////////////////////
Дз за 28 сентября
////////////////////////////
#include <iostream>
#include <cmath>

using namespace std;

#define task13

#ifdef task1
int main(){
    double x,y;
    cin >> x;
    if (x > 0){
        y = x + 1;
        cout << y << endl;
    }else if (x < 0){
        y = x - 2;
        cout << y << endl;
    }else{
        y = x + 10;
        cout << y << endl;
    }
    return 0;
}
#endif

#ifdef task2
int main(){
    double x,x1,x2;
    cin >> x >> x1 >> x2;
    int p = 0;
    int o = 0;
    if (x > 0){
        p ++;
    }else{
        o++;
    }if(x1 > 0){
        p++;
    }else{
        o++;
    }if(x2 > 0){
        p++;
    }else{
        o++;
    }
    cout << "положительных" << p << endl;
    cout << "Отрицательных" << o << endl;
   
    return 0;
}
#endif

#ifdef task3
int main(){
    double x,x1;
    cin >> x >> x1;
    if (x > x1){
        cout << x << endl;
    }else{
        cout << x1 << endl;
    }

    return 0;
}
#endif

#ifdef task4
int main(){
    double a,b,r,r1;
    cin >> a >> b;
    if (a > b){
        r = a - 2;
        r1 = b + 2;
    }
    cout << "Теперь А " << r <<" а B " << r1 << endl;
    return 0;
}
#endif

#ifdef task5
int main(){
    int n;
    cin >> n;
    int n1 = n / 100;
    int n2 = (n / 10) % 10;
    int n3 = n % 10;
    if (n1 > n2 > n3 ){
        cout << n2 << endl;
    }else if(n2 > n1 > n3){
        cout << n1 << endl;
    }else{
        cout << n3 << endl;
    }
    return 0;
    
}
#endif

#ifdef task6
int main(){
    double a,b,c,a1,b1,c1;
    cin >> a >> b >> c;
    a1 = a*2;
    b1 = b*2;
    c1 = c*2;
    if (a<b<c){
        cout << a1 << b1 << c1 << endl;
    }else if(a>b<c){
        cout << -a << -b << -c << endl;
    }
    return 0;
}
#endif

#ifdef task8
int main(){
    double x,r1,r2;
    cin >> x;
    r1 = 2*sin(x);
    r2 = 6-x;
    if (x > 0){
        cout << r1 << endl;
    }else if(x <= 0){
        cout << r2 << endl;
    }
    return 0;
}
#endif

#ifdef task9
int main(){
    double x,r1,r2;
    cin >> x;
    r1 = 2* x;
    r2 = -3 * x;
    if(x < -2){
        cout << r1 << endl;
    }else if(x > 2){
        cout << r1 << endl;
    }else{
        cout << r2 << endl;
    }
    return 0;
}
#endif

#ifdef task10
int main(){
    double x;
    cin >> x;
    if (x <= 0){
        cout << -x << endl;
    }else if (x<2){
        cout << pow(x,2) << endl;
    }else{
        cout << 4 << endl;
    }
    return 0;
}
#endif

#ifdef task11
int main(){
    double x;
    cin >> x;
    if(x < 0){
        cout << 0 << endl;
    } else if(x > 0){
        cout << 1 << endl;
    }else{
        cout << -1 << endl;
    }
    return 0;
}
#endif

#ifdef task12
int main(){
    int x;
    cin >> x;
    if((x % 400 == 0) || ((x % 4 == 0) && (x % 100 != 0))){
        cout << 366 << endl;
    }else{
        cout << 365 << endl;
    }
    return 0;
}
#endif
////////////////////////////
|
|
|
\/
ДЗ ЗА 5 ОКТЯРЯ
////////////////////////////
#include <iostream>
#include <cmath>

using namespace std;

#define task6

#ifdef task1
int main(){
    int n,s = 0;
    cin >> n;
    for(int i = 1;i <= n;i++){
        s += i;
        cout << s << endl;
    }
}
#endif

#ifdef task2
int main(){
    double s;
    for(int i = 1;i <= 25;i++ ){
        s= 1.5 * i;
        cout << s << endl;
    }
    return 0;
}
#endif

#ifdef task3
int main(){
    double s;
    for(int i = 5;i <=30;i= i + 5){
        s = 3.6 * i;
        cout << s << endl;
    }
    return 0;
}
#endif

#ifdef task4
int main(){
    double d;
    int s,t;
    cin >> s >> t;
    if (s < 1){
        return 1;
    }
    for(int i = 1;i <= t;i++){
        d = s * i;
        cout << d << endl;
    }
}
#endif

#ifdef task5
int main(){
    double s = 0.01,t_s=0;
    int d;
    cin >> d;
    if(d < 1){
        cout << "Введите больше 1" << endl;
        return 1;
    }
    for (int i = 1;i<=d;i++){
        s *= 2;
        t_s += s;
        cout << s << "\t" << "за"<< "\t" << i <<"\t" << "день" << endl;
    }
    cout << "всего"<< "\t" << t_s << endl;
    return 0;
}
#endif

#ifdef task6
int main(){
    double f,s = 0,s_k,p;
    int k,z_k,z = 0;
    cin >> f;
    if (f <10){
        return 1;
    }
    for(int i = 1;i <= f;i++){
        cout << "этаж" << "\t" << i<< "\t" << "сколько комнат" << endl;
        cin >> k;
        if (k < 1){
            return 1;
        }
        cout << "Ханято" << endl;
        cin >> z_k;
        k += s;
        z += z_k;
        s_k = s - z;
        p = z / k;
        cout << "всего" << k << "занятых" << z << "свободных" << s_k << "процент" << p<< endl;
    }
    
    return 0;
}
#endif
////////////////////////////
|
|
|
\/
ДЗ ЗА 25 ОКТЯРЯ
////////////////////////////
#include <iostream>
using namespace std;
#define task4
#ifdef task1
int main(){
    const int A = 5;
    int arr[] = {2,-3,6,4,0};
    int polo[A];
    int otrc[A];
    int p = 0;
    int o = 0;
    for(int i = 0;i < A;i++){
        cout << arr[i] << endl;
    }
    for(int i = 0;i < A;i++){
        if (arr[i] > 0){
            polo[p] = arr[i];
            p++;
            cout << "положительные" << arr[i] << endl;
        }else if(arr[i] < 0){
            otrc[o] = arr[i];
            o++;
            cout << "Отрицательные" << arr[i] << endl;
        }else{
            cout << "нули " << arr[i] << endl;
        }
    }
}
#endif

#ifdef task2
int main(){
    const int A = 5;
    int arr[A];
    int s = 0;
    for(int i = 0;i < A;i++){
        cin >> arr[i];
    }
    for(int i = 0;i < A;i++){
        if((arr[i]>0 && arr[i+1]> 0) || (arr[i]<0 && arr[i+1]<0)){
            cout << i << i+1 << endl;
            s++;
        }else if(arr[i] == 0){
            cout << "нет пар" << endl;
        }
    }
}
#endif

#ifdef task3
int main(){
    const int A = 5;
    int dlinna = 0;
    int arr[A] = {2,4,6,5,-3};
    for (int i = 0;i < A;i++){
        cout<< arr[i] << endl;
    }
    for (int i = 0;i < A;i++){
        if(arr[i]% 2 == 0){
            int new_dlinna = 1;
            for(int d = i + 1;d < A && arr[d] % 2 == 0;d++){
                new_dlinna++;
                cout << new_dlinna << endl;
            }
        }
    }
}
#endif

#ifdef task4
int main(){
    const int A = 5;
    int arr[A];
    for(int i = 0;i < A;i++){
        cin >> arr[i];
    }
    int max = arr[0];
    int m = 0;
    for(int i = 0;i< A;i++){
        if(arr[i] > max){
            max = arr[i];
            m = i;
        }
    }
    for(int i = m + 1;i< A;i++){
        arr[i] = 1;
    }
        

}
#endif

