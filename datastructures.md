# Structures and their Space/Time Complexities
| Data Structure | Access `O(f(n))` | Search ` | Insertion | Deletion |
| - | - | - | - | - |
| [Array](#array) | `O(1)` | `O(N)` | `O(N)` | `O(N)` |
| Stack | `O(N)` | `O(N)` | `O(1)` | `O(1)` |
| Queue | `O(N)` | `O(N)` | `O(1)` | `O(1)` |
| Singly Linked list | `O(N)` | `O(N)` | `O(1)` | `O(1)` |
| Doubly Linked List | `O(N)` | `O(N)` | `O(1)` | `O(1)` |
| Hash Table | `O(1)` | `O(1)` | `O(1)` | `O(1)` |
| Binary Search Tree | `O(log N)` | `O(log N)` | `O(log N)` | `O(log N)` |
| AVL Tree | `O(log N)` | `O(log N)` | `O(log N)` | `O(log N)` |
| B Tree | `O(log N)` | `O(log N)` | `O(log N)` | `O(log N)` |
| Red Black Tree | `O(log N)` | `O(log N)` | `O(log N)` | `O(log N)` |

## Array
| Pros | Cons |
| - | - |
| Most efficent space complexity | Fixed length, unscalable |

**Example:**
```c
int x[5] = {1,2,3,4,5};
```