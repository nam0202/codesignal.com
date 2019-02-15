```java
int makeArrayConsecutive2(int[] statues) {
    int min = statues[0],max = statues[0];
    int n = statues.length;
    for(int i=0;i<n;i++){
        if(statues[i]<min){
            min = statues[i];
        }
        if(statues[i]>max){
            max = statues[i];
        }
    }
    return max-min-n+1;
}
```