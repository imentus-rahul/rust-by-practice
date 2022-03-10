# 函数
1. 🌟🌟🌟
```rust,editable

fn main() {
    // 不要修改下面两行代码!
    let (x, y) = (1, 2);
    let s = sum(x, y);

    assert_eq!(s, 3);
}

fn sum(x, y: i32) {
    x + y;
}
```


2. 🌟🌟
```rust,editable
fn main() {
   print();
}

// 使用另一个类型来替代 i32
fn print() -> i32 {
   println!("hello,world");
}
```


3. 🌟🌟🌟

```rust,editable
// 用两种方法求解
fn main() {
    never_return();
}

fn never_return() -> ! {
    // 实现这个函数，不要修改函数签名!
    
}
```

> 你可以在[这里](https://github.com/sunface/rust-by-practice)找到答案(在 solutions 路径下) 