## Installation

```
$ gh extension install gh-cli-for-education/gh-assignments
```

## Usage

```
$ gh assignments --help
Usage: gh assignments [classroom name]
Description: List of assignments
```

## Example

```
➜  gh-assignments git:(main) gh pwd
ULL-ESIT-PL-2324
➜  gh-assignments git:(main) gh assignments
5 Assignments for ULL-ESIT-PL-2324

ID      Title                 Submission Public  Type   Deadline  Editor      Invitation Link                          Accepted  Submissions  Passing
547301  GitHub Campus Expert  false              group            codespaces  https://classroom.github.com/a/lK63sTPV  27        0            0
547528  GitHub Project Board  false              group            codespaces  https://classroom.github.com/a/GMvhYis6  16        0            0
547531  Visual Studio Code    false              group            codespaces  https://classroom.github.com/a/kH5wwS1N  14        0            0
547532  iaas                  false              group            codespaces  https://classroom.github.com/a/beBpKu83  13        0            0
550057  arith2js              false              group            codespaces  https://classroom.github.com/a/Jdvpp-ac  3         0            0
➜  gh-assignments git:(main) 
```