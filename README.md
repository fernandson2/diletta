
import 'dart:collection'

void main() {
  
  List<int> a = [1, 5, 2, 5, 2];
  Set valorH = HashSet();

  int add = -1;
  
  for(int i = 0; i < a.length; i++){
    
    
    bool rep = valorH.add(a[i]);
      
    if(rep == false){
      
       add = a[i];
       break;   
    }
   
  }
