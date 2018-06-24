# 26 Remove Duplicate from Sorted Array.md

```text
class Solution {
    public int removeDuplicates(int[] nums) {
        if (a.length == 0){
            return 0;
        }
        //base case i == 0
        int end = 0;
        //general case: i == 1 : n-1
        for(int i=1;i<a.length; i++){
            if(a[i] != a[i-1]){
                end++;
                a[end] = a[i];
            }
        }
        return end + 1;
    }
}

```





