# stack

Library of generic stack data structures for Go.

* [linked-stack](./linkedstack/)
* [slice-stack](./slicestack/)

## Install

```Go
$ go get github.com/golang-ds/stack
```

## Linked Stack

Underlying data structure: singly-linked-list

### Import

```Go
import "github.com/golang-ds/stack/linkedstack"
```

### Use

```Go
s := stack.New[int]()
s.Push(1)
```

## Slice Stack

Underlying data structure: slice

### Import

```Go
import "github.com/golang-ds/stack/slicestack"
```

### Use

```Go
s := stack.New[int]()
s.Push(1)
```