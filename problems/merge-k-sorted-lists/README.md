<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../generate-parentheses "Generate Parentheses")
　　　　　　　　　　　　　　　　
[Next >](../swap-nodes-in-pairs "Swap Nodes in Pairs")

## [23. Merge k Sorted Lists (Hard)](https://leetcode.com/problems/merge-k-sorted-lists "合并K个升序链表")

<p>Given an array of linked-lists lists, each linked list is sorted in ascending order.</p>

<p>Merge all the linked-lists into one sort linked-list and return it.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> lists = [[1,4,5],[1,3,4],[2,6]]
<strong>Output:</strong> [1,1,2,3,4,4,5,6]
<strong>Explanation:</strong> The linked-lists are:
[
  1-&gt;4-&gt;5,
  1-&gt;3-&gt;4,
  2-&gt;6
]
merging them into one sorted list:
1-&gt;1-&gt;2-&gt;3-&gt;4-&gt;4-&gt;5-&gt;6
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> lists = []
<strong>Output:</strong> []
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> lists = [[]]
<strong>Output:</strong> []
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>k == lists.length</code></li>
	<li><code>0 &lt;= k &lt;= 10^4</code></li>
	<li><code>0 &lt;= lists[i].length &lt;= 500</code></li>
	<li><code>-10^4 &lt;= lists[i][j] &lt;= 10^4</code></li>
	<li><code>lists[i]</code> is sorted in <strong>ascending order</strong>.</li>
	<li>The sum of <code>lists[i].length</code> won&#39;t exceed <code>10^4</code>.</li>
</ul>

### Related Topics
  [[Heap](../../tag/heap/README.md)]
  [[Linked List](../../tag/linked-list/README.md)]
  [[Divide and Conquer](../../tag/divide-and-conquer/README.md)]

### Similar Questions
  1. [Merge Two Sorted Lists](../merge-two-sorted-lists) (Easy)
  1. [Ugly Number II](../ugly-number-ii) (Medium)
