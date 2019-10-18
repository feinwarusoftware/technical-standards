- js rules
- ts rules
- js/ts rules

2 spaces indent
double quote strings
template strings only for templates
no unused vars
dont use var
always use const unless you wanna change the var
> avoid function side effects
- avoid accessing (read) vars outside of function scope
- DO NOT write vars outside of function scope
space after keywords
no space before fn decl
always use === instead of ==, except when comparing to null/undefined
infix ops spaced
space after comma
no dnagling comma
else statement same line as }
prefer return over else
x indentation limit (TBD
x line char limit (TBD)
always use curly brackets for ifs (use ternary for 1 liners)
no nester ternary
react: avoid logic in render() return
prefer promises over callbacks
handle callback errors
declare browser globals with global comment
no multiple blank lines
end each file with blank line
CRLF line endings
operator line break
each var, own statement
no cond assignment
spaces in single line blocks
camelcase for vars, fns, pascalcase for classes (constructors)
comma end of line
dot with prop
no func call spacing
space between colon and value
no arg constructor invoked with ()
object getter when setter defined
only constructors of derived classes call super, these must call it
avoid array constructor
no arguments caller/calee
no class assign
no const assign (as if it would let you do that anyway lel)
no const expressions in cond, except loops
no control regex
no debugger statements
no delete operator on vars
no dupe args
no dupe class members
no dupe case labels
single import statement per module
no empty char regex
no empty destructuring
no eval
no reassign in exception catch
no extend native
no extra bind*
no unnecessary boolean cast
no unnecessary func parens
no switch fallthrough
no floating decimal
no func reassign
no global reassign
no implied eval
no func decl in nested blocks (declare all func in glob if possible)
no invalid regex
no trailing whitespace
no __iterator__
no label, no label var
no unnecessary nested blocks
{} style
dont mix space + tab indent
no multiline strings
no multi spaces
no new without var assignment
dont use Function() constructur
dont use Object() constructur
no new require
no new Symbol()
dont use primitive wrapper instances
no octal
no obj calls
no octal escape
no path concat
dont use __proto__
dont redeclare vars
descriptive var names
no regex spaces
return assignment parens
no self assign
no sequences (avoid comma operator)
no self compare
no shadpw restricted
no sparse arrays
no tabs
no template curly in string
super() before this
only throw Error object
no undef int (prefer null over undefined - cmp + assign)
no unmodified loop cond
dont use ternary if simpler alternatives exist
no unreachable code
no flow control statements in finally
no unsafe negation
no useless call/apply
no useless computed key
no useless constructor
no useless escape
no useless rename
no whitespace before prop
no with statement
object prop newline
no padding in blocks
no whitespace before spread
; space after, not before
space before blocks
no space in parens
space after unary ops
spaced comments
no template curly spacing
only isNaN() to check NaN
typeof valid comp
wrap iife
yield star spacing (but avoid yield anyway)
avoid yoda conditions
always use ;
no unexpected multiline (examples from website)
no dead code

- node repo setup (with/without ts)
  - basic starter repo
- web repo setup (with/without ts)
  - react
  - webpack
  - other configs
  - basic starter repo
- mobile repo setup (with/without ts)
  - react native
  - basic starter repo
- desktop repo setup (???)
  - basic starter repo

- c/cpp/cs style guides
- rust style guides
- reasonml style guides

- any repo setup on github guidelines, boards, etc.
  - basic starter repo with stuff
