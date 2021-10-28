Design:

Implemented B+tree with one extension:
We implemented all key types in record manager.

Inside the b-tree file, page 0 is the meta data node. And from page 1 on, it's the page content node.

Implementation:

We implemented all methods as required and test cases passed. With one exception:

printTree()

We implemented so that it doesn't return char* but instead will print everything directly to console. We added a few printTree()'s in the test file to see the result. And it prints well.

Late:
We submitted the documentation a little bit past mid-night Dec 2. We hope that won't make us lose points.

Compile & run
>make
>./test_assign4_1
