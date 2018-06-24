# L1 线1 leetcode 26/27/80/38/228/151/163 6月24上午

出题人  


模型    

线        for\(...\)        while\(...\)

树        DFS bottom up        DFS top down        BFS

图        DAG        DFS-&gt;DP        BFS        DG/VG    \(BF\)

破题: 所有题都可以用 Math Induction 数学归纳法

f\(a\[0-&gt;i\]\)+op a\[i\] -&gt; f\(a\[i+1\]\)  


for循环 课本上示例代码数组元素求和result初始化为0 求数组元素积result初始化为1

因为求和时 引入i=-1的伪base case,  f\(-1\) = 0 Si=f\(i-1\)+f\(i\), 符合数学归纳法

求积 f\(-1\)=1



26 Remove Duplicate from Sorted Array

录音9:09 - 9:56

27 Remove Element

80 Remove Duplicates from Sorted Array II

录音9:56 - 10:27

38. count and say

录音 10:59 - 11:29

228. Summary Ranges

录音 11:32 - 11:49

151. Reverse Words in a String 重点题 每天复习一遍 facebook常考

录音 11:54 - 12:52

163: Missing Ranges

新建类写解法时可以用interface为同一个题提供多种解法, 记录自己的进步

