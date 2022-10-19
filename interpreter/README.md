The Uni programming language is a simple programming language for educational purposes.

## How to install
Build the interpreter from the source-code. In order to build it from the source-code, you need `git`, and `go` version 1.19 or later. Run the following commands to build from the source-code:
```sh
git clone https://github.com/parsaakbari1209/uni-lang.git
cd uni-lang
go build -o uni
```
---
## How to use
The uni-lang uses `.uni` suffix(e.g. `main.uni`). Use the following command to execute a uni-lang source-code:
```sh
// Linux
./uni main.uni
```
---
## Syntax
### Comments
```
# This is a comment!
```
### Boolean
```
true
!true
true or true
true and true

false
!false
false or false
false and false

true or false
false or true
true and false
false and true
```
### Number
```
1
-1
1 + 2
1 - 2
1 * 2
1 / 2

1.5
-1.5
1.1 + 2.2
1.1 - 2.2
1.1 * 2.2
1.1 / 2.2

1 + 2.2
1 - 2.2
1 * 2.2
1 / 2.2
```
### String
```
"Hello World!"
"Hello" + " " + "World" + "!"
```
### Variable
```
num = 0
str = "Hello World!"
```
### Array
```
num = [0, 1, 2]
num[0]

str = ["Hello", "World", "!"]
str[0]

mix = [1, "Hello", 1.5, "World"]
mix[0]
```
### Map
```
data = {"slug": "Hello World!", "version": 1}
data["slug"]
```
### Condition
```
if a == b {
    // ...
}

if a == b {
    // ...
} else {
    // ...
}
```
### Loop
```
while true {
    // ...
}

for i in (1, 5) {
    // ...
}

for i in "Hello World" {
    // ...
}

var arr = ["Hello", "World", "!", 1]
for i in arr {
    // ...
}
```
### Function
```
fn sum(a, b) {
    return a + b
}
sum(1, 2)
```
### Built-in
```
len("Hello World!")
len(["Hello", "World", "!"])
len({1: "Hello", 2: "World", 3: "!"})
print("Hello World!")
println("Hello World!")
```
---
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.  
Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
