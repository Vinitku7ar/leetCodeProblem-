class Solution {
public:
    void sortColors(vector<int>& num) {
int low=0;
int mid=0;
int high =num.size()-1;
while(mid<=high){
          if(num[mid]==0){
               swap(num[low],num[mid]);
               low++; mid++;}
         else if(num[mid]==1){
                mid++;}
         else{
                  swap(num[high],num[mid]);
                         high--;
                     }
            }

        
    }
};
