# Cycle detection

A linked list is said to contain a cycle if any node is visited more than once while traversing the list.

Complete the function `hasCycle(SinglyLinkedListNode head)` below.

```java
class SinglyLinkedListNode {
    SinglyLinkedListNode next;
}

boolean hasCycle(SinglyLinkedListNode head) {
}
```

It has one parameter: a pointer to a Node object named `head` that points to the head of a linked list. Your function must return a boolean denoting whether or not there is a cycle in the list. If there is a cycle, return `true`; otherwise, return `false`.

Note: If the list is empty, `head` will be null.

If the list contains a cycle, your function must return `true`. If the list does not contain a cycle, it must return `false`.

## Samples

### Inputs

![Linked Lists](https://raw.githubusercontent.com/FabienLauf/code-at-home/master/img/linkedLists.png)

### Outputs

    false
    true
