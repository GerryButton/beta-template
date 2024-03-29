# Formatting comparison

BB = Bitbucket
GH = Github

## Heading

Headings requires space separator in Github

##H1 (not a header in GH)
##H2 (not a header in GH)
## H3
## H4

---
## List

Lists need a blank line in BB

* item 1
* item 2

Blank line not needed in GH 
* item 1
* item 2

---


## Table
Tables need balanced delimiters | in Github

Bad:

|Type         | SI unit   | Description               |
| :---        |    :----:   |          :---           |
|LENGTH        |	metres      |Length metric, used for coordinates.  |
|TIME          |seconds      |Time metric.       |
|FORCE         |Newton       |Force metric.
|ANGLE         |radians      |Angle.              |
|NORMALIZED    |             |Percentage, expressed as a fraction (1.0 = 100%). |
|LOGICAL_VALUE |             |Logical boolean value. |

Good:

|Type         | SI unit   | Description               |
| :---        |    :----:   |          :---           |
|LENGTH        |	metres      |Length metric, used for coordinates.  |
|TIME          |seconds      |Time metric.       |
|FORCE         |Newton       |Force metric. |
|ANGLE         |radians      |Angle.              |
|NORMALIZED    |             |Percentage, expressed as a fraction (1.0 = 100%). |
|LOGICAL_VALUE |             |Logical boolean value. |

---

## Embedded images

- Github filename is case sensitive
- Relative paths handled differently in Typora/MarkdownEdit/Notepad++

(media/github.png) - preferred method
![description](media/github.png)

(/media/github.png)
![description](/media/github.png)

(./media/github.png)
![description](./media/github.png)

Notepad++ MardownViewer++:
(file:///./media/github.png)
![description](file:///./media/github.png)

---

## Graphics

Html characters not supported in BB: e.g. &#8593;

## Link to a different page

[Click here to open docs/readme.md](docs/README.md)
