---
layout: single
title: "Quick Sort"

categories:
    - code-test

permalink: /code-test/quick-sort/
sidebar:
  nav: "categories"

---

use pivot and partition to swap

1. in the list, place a pivot at the very right side
2. make index pointers for both left and right side of the list
3. increase/decrase the index pointers of the list until it breaks the both condition, if true, swap each other

      Swap Conditions
      * Left pointer must be smaller than pivot
      * Right pointer must be larger than pivot

4. continue step 3 until the pointers cross each other, and swtich the position of first index of right section and where pivot value is
5. First partinioning finished, and continue the same steps for left list and right list that was separated by this pivot number

Best : O($nlogn)\
Worst : O($n^2$)\
Average : O($nlogn$)
