class Solution {
    public int[] buildArray(int[] nums) {
        int ans[]=new int[nums.length];
        for(int i=0;i<nums.length;i++)
        {
            ans[i]=nums[nums[i]];
        }
        return ans;// [0,1,2,4,5,3]
    }
}
