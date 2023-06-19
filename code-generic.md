# Generic Code Standards

## Todo
```
// @todo(jae) implement foobah protocol
```
Todo is used throughout code to signify a new feature that needs to be implemented or a addition to some method/object etc. Todo should not be used for bugs or other references.

A todo follows the regex below which equates to the comment symbol and optional space, the string '@todo` (case insensitive) the name, email or taskid in parenthesis followed by a space and the message of what/why something is todo

## Ref
```
// @ref(https://tools.ietf.org/html/rfc2324#section-2.3.2) 2324:Hyper Text Coffee Pot Control Protocol (HTCPCP/1.0): Semantics and Content
```
Ref is used for referencing an external (from the repo) source it can be almost anything from an RFC to a bug in the tracker to a stack overflow post that helped you, add the title or comment for other devs to understand context 
A re follows the regex below which equates to the comment symbol and optional space, the string '@ref` (case insensitive) a link or other reference in parenthesis followed by a space and the message of what/why the ref

## Regex
```
// @regex(`^[0-9a-zA-Z]{3,15}$`, https://regexr.com/7fl8m) checks string is alphanumeric (case-insensitive) and between 3 and 15 chars 
```
Regex should be used wherever a regex pattern is in code, it requires 3 parts, the pattern, the reference and the explaination:
- the pattern in question so it is isolated from code
- a reference to what the pattern ACTUALLY does, this is useful for validation
- explaination of what the regex is SUPPOSED to do, as this may not actually match what the pattenr does 

## Bug
```
// @bug(1234) 1/32 chance of loading in wrong order,  
```
for minor bugs that wont break anything but should be fixed at some point, or is out of scope for current work


## Allowed 
allowed is to be used only when a ENUM or similar is not available I.e yaml, this will quickly get out of date so caution is advised
```
// @alloed(apple,orange,pear,watermelon)
```
