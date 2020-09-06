# 十分有用但不常用的工具

## [Rubular](https://rubular.com/): A Ruby regular expression editor

Rubular uses Ruby 2.5.7.

### Regex quick reference

| Syntax   | Description                                  | Syntax | Description                                     |
|----------|----------------------------------------------|--------|-------------------------------------------------|
| [abc]    | A single character of: a, b, or c            | \D     | Any non-digit                                   |
| [^abc]   | Any single character except: a, b, or c      | \w     | Any word character (letter, number, underscore) |
| [a-z]    | Any single character in the range a-z        | \W     | Any non-word character                          |
| [a-zA-Z] | Any single character in the range a-z or A-Z | \b     | Any word boundary                               |
| ^        | Start of line                                | (...)  | Capture everything enclosed                     |
| $        | End of line                                  | (a\|b) | a or b                                          |
| \A       | Start of string                              | a?     | Zero or one of a                                |
| \z       | End of string                                | a*     | Zero or more of a                               |
| .        | Any single character                         | a+     | One or more of a                                |
| \s       | Any whitespace character                     | a{3}   | Exactly 3 of a                                  |
| \S       | Any non-whitespace character                 | a{3,}  | 3 or more of a                                  |
| \d       | Any digit                                    | a{3,6} | Between 3 and 6 of a                            |

options:

- i: case insensitive
- m: make dot match newlines
- x: ignore whitespace in regex
- o: perform `#{...}` substitutions only once

## [crontab guru](https://crontab.guru/): Quick and simple editor for cron schedule expressions

The quick and simple editor for cron schedule expressions by [Cronitor](https://cronitor.io/cron-job-monitoring).

- `*`: any value
- `,`: value list separator
- `-`: range of values
- `/`: step value

## [TinyPNG](https://tinypng.com/): Smart PNG and JPEG compression

## [WebSequenceDiagrams](https://www.websequencediagrams.com): Create sequence diagrams in seconds

文字描述的时序图绘制工具，[示例](https://www.websequencediagrams.com/examples.html)。

## [Isoflow](https://isoflow.io/): Create beautiful cloud diagrams in minutes

云服务示意图绘制工具。

![isoflow](./_images/isoflow.png)

## [Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables)

在线编辑并生成对齐的 Markdown table 数据。
