# Generic Code Standards

## Todo
```
// @todo(jae) implement foobah protocol
```
Todo is used throughout code to signify a new feature that needs to be implemented or a addition to some method/object etc. Todo should not be used for bugs or other references.

A todo follows the regex below which equates to the comment symbol and optional space, the string '@todo` (case insensitive) the name, email or taskid in parenthesis followed by a space and the message of what/why something is todo
```
REGEX:
```

## Ref
```
// @ref(https://tools.ietf.org/html/rfc2324#section-2.3.2) 2324:Hyper Text Coffee Pot Control Protocol (HTCPCP/1.0): Semantics and Content
```
Ref is used for referencing an external (from the repo) source it can be almost anything from an RFC to a bug in the tracker to a stack overflow post that helped you, add the title or comment for other devs to understand context 
A re follows the regex below which equates to the comment symbol and optional space, the string '@ref` (case insensitive) a link or other reference in parenthesis followed by a space and the message of what/why the ref
```
REGEX:
```

## Bug
```
// @bug(1234) 1/32 chance of loading in wrong order,  
```
for minor bugs that wont break anything but should be fixed at some point 
