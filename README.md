## 20年，从未忘记！81192，请返航
#### 又是一年4月1日 81192，请返航！请回家！

[81192请返航](https://mbd.baidu.com/newspage/data/landingsuper?context=%7B%22nid%22%3A%22news_9824726861978634365%22%7D&n_type=0&p_from=1)

![alt 81192我们继续前进](https://pics6.baidu.com/feed/bd315c6034a85edfd5a1658e065e412bdd547504.jpeg?token=62345fb8ea8bd0f8067e5f27a77d6a22)

[第一章节笔记](notes/note1.md)

```C
int* twoSum(int* nums, int numsSize, int target, int* returnSize){
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

>81192，不仅仅是一架飞机
>更是中国军人的精神——
>不惧对手，英勇亮剑！
>“我已无法返航你们继续前进”

* Asterisks 1
* Asterisks 2
* Asterisks 3
+ Plus signs 1
+ Plus signs 2
+ Plus signs 3
- Minus signs 1
- Minus signs 2
- Minus signs 3
