- 👋 Hi, I’m @Deva-cell
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Deva-cell/Deva-cell is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>
int removeDuplicates(int* arr, int arrSize) {
 if(arrSize == 0){
    return 0;
 }
 int j = 0;
 for(int i=1; i<arrSize; i++){
    if(arr[i] != arr[j]){
        j++;

        arr[j] = arr[i];
    }
 }
 return j+1;
}





