---
title: "Markdown Lists"
date: 2020-05-25T20:24:23-07:00
Description: ""
Tags: []
Categories: []
Series: []
---


## Unordered List

```
Unordered List

- item 1
    * item A
    * item B
        more text
        + item a
        + item b
        + item c
    * item C
- item 2
- item 3
```

Unordered List

- item 1
    * item A
    * item B
        more text
        + item a
        + item b
        + item c
    * item C
- item 2
- item 3


## Ordered List

```
Ordered List

1. item 1
    1. item A
    2. item B
        more text
        1. item a
        2. item b
        3. item c
    3. item C
2. item 2
3. item 3
```

Ordered List

1. item 1
    1. item A
    2. item B
        more text
        1. item a
        2. item b
        3. item c
    3. item C
2. item 2
3. item 3

## Task List

```
Task List

- [X] item 1
    * [X] item A
    * [ ] item B
        more text
        + [x] item a
        + [ ] item b
        + [x] item c
    * [X] item C
- [ ] item 2
- [ ] item 3
```

Task List

- [X] item 1
    * [X] item A
    * [ ] item B
        more text
        + [x] item a
        + [ ] item b
        + [x] item c
    * [X] item C
- [ ] item 2
- [ ] item 3

## Mixed Lists

`Really Mixed Lists` should break with `sane_lists` on.

```
Mixed Lists

- item 1
    * [X] item A
    * [ ] item B
        more text
        1. item a
        2. itemb
        3. item c
    * [X] item C
- item 2
- item 3


Really Mixed Lists

- item 1
    * [X] item A
    - item B
        more text
        1. item a
        + itemb
        + [ ] item c
    3. item C
2. item 2
- [X] item 3
```

Mixed Lists

- item 1
    * [X] item A
    * [ ] item B
        more text
        1. item a
        2. itemb
        3. item c
    * [X] item C
- item 2
- item 3


Really Mixed Lists

- item 1
    * [X] item A
    - item B
        more text
        1. item a
        + itemb
        + [ ] item c
    3. item C
2. item 2
- [X] item 3


## Dictionary

```
Dictionary
:   item 1

    item 2

    item 3
```

Dictionary
:   item 1

    item 2

    item 3
