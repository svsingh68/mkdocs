# About this page:

A demo for use of mkdocs as repository creation.

## 1. Abbreviations
```bash
*[HTML]: hypertext markup language
*[FACTS]: flexible ac transmission system

Here is an example of HTML and FACTS abbreviations to be used.
HTML, html ot Html three words are used.
```

*[HTML]: hypertext markup language
*[FACTS]: flexible ac transmission system

Here is an example of HTML and FACTS abbreviations to be used.
HTML, html ot Html three words are used.

---
## 2. Adding admonitions/notations
This feature can be useful in documentation process.

Use of `???` and `!!!` is used with the appropriate tags
entered in the `mkdocs.yml`. Using `inline` qualifier is also
useful.

```bash
!!! note "Making a note using Fontawesome notations"
    This is a note.
```
!!! note "Making a note using Fontawesome notations"
    This is a note.

---

!!! tip inline end "Making a note inline"
    This is a end-inline tip.

```bash
!!! tip inline end "Making a note inline"
    This is a end-inline tip.
```

---

!!! danger inline  "Making a note inline"
    This is a start-inline danger.

```bash
!!! danger inline "Making a note inline"
    This is a start-inline danger.
```


---

Sub-sectioning of the notations can also be done

```bash
??? danger "Nested Danger notations"
    This is danger
    ??? warning "Collapsed formatting"
        This is a sub-warning
    ???+ tip "Expanded version of a message"
            This is a tip
```

??? danger "Nested Danger notations"
    This is danger
    ??? warning "Collapsed formatting"
        This is a sub-warning
    ???+ tip "Expanded version of a message"
            This is a tip
---

Other  notations which can be useful are:

!!! bug   
!!! note
!!! success
!!! failure

## 3. Annotations

!!! note annotate "Phasellus posuere in sem ut cursus (1)"

    Lorem ipsum dolor sit amet, (2) consectetur adipiscing elit. Nulla et
    euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo
    purus auctor massa, nec semper lorem quam in massa.

1.  :man_raising_hand: I'm an annotation!
2.  :woman_raising_hand: I'm an annotation as well!


This feature can be very useful when discussing various
attributes of the same subject for comparison.
This is an annotation (1) for example.
{.annotate}
1.:This is an annotation.

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```


---
s
