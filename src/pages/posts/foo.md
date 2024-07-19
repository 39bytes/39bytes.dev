---
layout: ../../layouts/PostLayout.astro
title: Functor, Applicative and Monad in Rust
author: Me
description: "Testing things with the blog functionality"
date: 2022-08-08
tags: ["foo", "bar"]
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


```haskell
instance Applicative Maybe where
    pure = Just
    (Just f) <*> (Just x) = f x
    _ <*> _ = Nothing
```
