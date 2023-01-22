---
title: 🕹 Breakout
description: Classic arcade game made in Rust
date: 2022-07-21
---

## Breakout

Few days ago I watched a <a href="https://www.youtube.com/watch?v=xQ9YTY7ZgsI" target="_blank">video</a> on YouTube about re-making a version of the classic arcade game Breakout with Rust. Since I love Rust, I decided to make it and improve it!
<!-- more -->
<br>

Here you can play the first version of my game:

<style>
    #glcanvas {
        margin: 0px;
        padding: 0px;
        width: 100%;
        height: 500px;
        background: black;
        z-index: 0;
    }
</style>


<canvas id="glcanvas" tabindex='1'></canvas>
<br><br>
Hope you had fun!
<br><br>
Soon new functionalities will be available and I will release the source code on GitHub!

<!-- Minified and statically hosted version of https://github.com/not-fl3/macroquad/blob/master/js/mq_js_bundle.js -->
<script src="https://not-fl3.github.io/miniquad-samples/mq_js_bundle.js"></script>
<script>load("/breakout.wasm");</script> <!-- Your compiled wasm file -->