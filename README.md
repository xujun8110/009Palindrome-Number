# 009Palindrome-Number
判断回文数，有好多种方法，这种最简单了吧

public class Solution {
    public boolean isPalindrome(int x) {

        String s1 = String.valueOf(x);
        StringBuffer sb = new StringBuffer(s1);
        String s2 = sb.reverse().toString();
        if(s1.equals(s2))
          return true;
        else
          return false;
    }
}
