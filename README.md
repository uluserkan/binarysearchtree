# Proje 3 - Binary Search Tree - Kodluyoruz

Base of Problem: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

We select first element for Index (Root) element as 7 (Seven)

So, after this selection, we are creating tree modal;

First Step: We put 7 as root on top level of tree and after this, we are asking to root, other elements is grater or smaller than you. If it is grater than it, we put it on right side on tree's second leve. Else, if it is smaller than root, we put it to left side on trees next level.

Second Step: 5 is smaller than root (7) so, we put it left side on next tree level. Asking for 1, it is smaller than 7 and we are going to left level. But there is 5 element here, we are asking to 5 for 1. 1 is smaller than 5, so, we put 1 element to, 5 elements left side on next tree level.

Thith Step: 8 is grater than root (7). We put 8 element to root's right side on nect tree level.In continue, 3 element is smaller then root (7) and when we look next level, we are seeing 5 elemnt and 3 is smaller than 3 element, continue its next level, at this time we are seeing 1 element and 3 is greater than 1 element. So, we put the 3 element on 1 elements right side on next tree level.

Fourth Step: Six element is smaller than root (7) but, at the next level, greater than 5. So, we put it on 5 element's right side at next level. And zero is smaller then root (7), in continue, it is smaller than 5 element and under level this, it smaller than 1 element. So, we put it under 1 element's left side.

Fifth Step: 9 element is greater than root (7) so, we are going to its right side. We are seeing 8 element at this level but, our 9 lement is greater than this, so we put it next tree level and 8 elemen't right side. 4 element's own steps from root to its suitable isae are; smaller, smaller, greater, greater. So, we put it 3 elemen'ts next tree level and right side.

Sixth Step: 2 element's steps same as the 4 elements steps until last step. At the last step, it is smaller than 3 element and we put it 3's sub-level on tree and 3's left side.


Binary Search Tree for This Problem;

             7
            / \
           5   8
         /  \    \
       1     6     9
      / \         
    0     3           
        /   \
      2       4
