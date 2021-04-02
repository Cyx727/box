## 20年，从未忘记！81192，请返航
#### 又是一年4月1日 81192，请返航！请回家！

[81192请返航](https://mbd.baidu.com/newspage/data/landingsuper?context=%7B%22nid%22%3A%22news_9824726861978634365%22%7D&n_type=0&p_from=1)

![alt 81192我们继续前进](https://pics6.baidu.com/feed/bd315c6034a85edfd5a1658e065e412bdd547504.jpeg?token=62345fb8ea8bd0f8067e5f27a77d6a22)

[第一章节笔记](notes/note1.md)

```int* twoSum(int* nums, int numsSize, int target, int* returnSize){
    int* ans=(int*)malloc(sizeof(int)*numsSize);
    for(int i=0;i<numsSize-1;i++){
        for(int j=i+1;j<numsSize;j++){
            if(nums[i]+nums[j]==target){
                ans[0]=i;
                ans[1]=j;
                *returnSize=2;
                return ans;
            }
        }
    }
    return 0;
}
```
