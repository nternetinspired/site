---
title: "Go Error Handling"
date: 2020-07-31T14:44:26+05:30
tags: [go, errors]
draft: true
summaryImage: "errors.png" 
keepImageRatio: true
toc: true
categories: [go]
summary: "Error Handling in golang"
---

## Errors in Go
Errors are the mistakes or faults in the program that causes our program to behave unexpectedly. In any programming languages errors are mainly categorized as below
- Syntax Errors
- Semantic Errors(static and dynamic)
- Logical Errors
- Runtime Errors

In Golang, An error is just a value that a function can return if something unexpected happened.

## Errors Users
- developers
- end-users
- programs

## Error handling

If err != ni {
    
}



## Error Interface
Error interface is defined inside go standard library 
{{< codeWide language="go" >}}
type error interface {
	Error() string
}
{{< /codeWide >}}

## Returning Errors
There are two ways to return errors
{{< codeWide language="go" >}}
fmt.Errorf("Error Message")
errors.New("Error Message")
```

## Custom Errors


