```java
boolean checkPalindrome(String inputString) {
    int leng = inputString.length();
    for(int i=0;i<leng/2;i++){
        if(inputString.charAt(i)!= inputString.charAt(leng-i-1)){
            return false;
        }
    }
    return true;
}
```