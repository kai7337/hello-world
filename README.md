# hello-world

// Author Kai Choi
// Description: Hello World in C++
//============================================================

#include <iostream>
  using namespace std;
  
  int hello1Function(string name1);
  int hello2Function(string name2);
 //main
  int main(){
  string name1="your name1";
  
  hello1Function(name1);
  
  string name2="your name2";
  
  hello2Function(name2);
  
  return 0;
  }
  

  /** hello1Function.cpp**/
  
  #include<iostream>
  
  usingnamespacestd;
  
  inthello1Function(stringname1){
    cout << "hello World "<< name1 << endl;
    return 0;
  }
  
  
  
  /** hello2Function.cpp**/
  
  #include <iostream>
  using namespace std;
  inthello2Function(stringname2){
    cout << "hello World "<< name2 << endl;return0;
  }
