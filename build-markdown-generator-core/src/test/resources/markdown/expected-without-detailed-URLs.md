## Build report

### JUnit

:cloud: 3/5 tests passed, over 0.01 seconds.

| Test | Message | Time |
| ---- | ------- | ---- |
| :small_blue_diamond: `com.some.test.MyClassTest.test_something3` | FAIL! | 0.003 |
| :small_red_triangle: `com.some.test.MyClassTest.test_something4` | ERROR! | 0.002 |

### Checkstyle

:warning: 2 violations found.

| Class | Line | Message |
| ----- | ---- | ------- |
| MyClass.java | 3 | Missing JavaDoc. |
| SomeOtherClass.java | 15 | Redundant newline(s). |

### Coverage

* :star: `82.26%` of all lines covered (`51/62`)
* :boom: `75%` of all branches covered (`12/16`)
