# -Python-program-to-construct-the-following-pattern-using-a-nested-for-loop.
.CODING
n=5;
for i in range(n):
for j in range(i):
print (&#39;* &#39;, end=&quot;&quot;)
print(&#39;&#39;)
for i in range(n,0,-1):

for j in range(i):
print(&#39;* &#39;, end=&quot;&quot;)
print(&#39;&#39;)
Output:
*
* *
* * *
* * * *
* * * * *
* * * *
* * *
* *
*

