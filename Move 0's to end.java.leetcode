Input: nums = [0,1,0,3,12]
Output: [1,3,12,0,0]

class Solution {
    public void moveZeroes(int[] nums) {
        int j = -1;
        for(int i=0;i<nums.length;i++){
            if(nums[i]==0){
                j=i;
                break;
            }
        }
        if(j==-1) return;
        for(int i=j+1; i<nums.length;i++){
            if(nums[i]!=0){
                nums[j] = nums[i];
                nums[i]=0;
                j++;
            }
        }
        System.out.print(nums);
    }
}
