---
layout: ../../layouts/PostLayout.astro
title: Testing
author: Me
description: "Testing things with the blog functionality"
date: 2022-08-08
tags: ["foo", "bar"]
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Heading 1
content under heading 1

## Heading 2

content under heading 2
### Heading 3

content under heading 3

#### Heading 4

content under heading 4

##### Heading 5

content under heading 5

###### Heading 6

content under heading 6


```haskell
instance Applicative Maybe where
    pure = Just
    (Just f) <*> (Just x) = f x
    _ <*> _ = Nothing
```

```rust
use std::sync::{Arc, Mutex};

struct MyThing {
    foo: Arc<Mutex<Vec<u32>>>;
}

enum OtherThing {
    Foo(Vec<u8>),
    Bar(u32),
    Baz(u16),
}

macro_rules! bruh {

}

fn main() {
    println!("Hello World");
}
```
