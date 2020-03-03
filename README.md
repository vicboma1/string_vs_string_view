# string vs string_view


it -> 1

| Function   |      Milliseconds      |  Microseconds |
|----------|:-------------:|------:|
| substring  |  1867 | 1867451 |
| substring_view  |    13   |   13608 |
| substring_view_const  | 9 |    9614 |


it -> 2

| Function   |      Milliseconds      |  Microseconds |
|----------|:-------------:|------:|
| substring  |  1746 | 1746522 |
| substring_view  |    12   |   12727 |
| substring_view_const  | 9 |    9970 |

it -> 3

| Function   |      Milliseconds      |  Microseconds |
|----------|:-------------:|------:|
| substring  |  1795 | 1795858 |
| substring_view  |    11   |   11767 |
| substring_view_const  | 8 |    8827 |
