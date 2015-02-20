# Project ideas

urbit is a complete computing stack written from scratch. arvo, our operating system, is written in hoon, our programming language, which is a thin wrapper around nock, our equivalent of assembly. Everything runs inside a virtual machine on top of unix. 

Naturally, the majority of these projects will require writting hoon at either intermediate or advanced levels. We definitely do *not* expect students to have previous experience in hoon. Having some functional programming experience can be helpful, but even that is not really needed. It is easy to pick up. Last year we had several interns, all of whom were up to speed within two weeks.

---

## Expand the library of API connectors for urbit

### Brief description

At the moment your data is spread out across cloud services. With a personal cloud computer like urbit, you should be able to control all of these services from one place. The framework for doing this in urbit is in place, and the more outside data types we can handle the better. 

### Difficulty

Medium. Student should be familiar with common web APIs, and will need to program in hoon.

### Mentor

Galen Wolfe-Pauly

---

## Run JS in urbit

### Brief description

Because urbit can also be accessed through a browser we use a lot of JavaScript. To make the development of client-side urbit applications smoother it would be great to implement JavaScript / ES5 inside of urbit and bind it to V8 or equivalent. 

### Difficulty

Medium-hard. Student would need to learn hoon quite thoroughly. Student would also need either a strong languages background or have a lot of JS experience.

### Mentor

Curtis Yarvin

---

## hoon language improvements

### Brief description

There are a large set of rough spots and small weaknesses in the hoon language. Better comprehension macro libraries, better container libraries, improved defaulting, memoization at the compiler layer and so on. 

### Difficulty

Medium-hard. Student would need a solid FP background and the desire to gain a deep knowledge of the hoon langauge.

### Mentor

Curtis Yarvin

---

## Floating point in hoon

### Brief description

Our support of floating point is rudimentary at present. It would be ideal to build not just fully fleshed-out floating point support, but also a well-chosen set of standard primitives with C implementations to boot. Ideally similar to the BLAS library: http://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms.

### Difficulty

Hard. Student would need to learn the hoon langauge thoroughly and have at least rudimentary C skills. 

### Mentor

Curtis Yarvin

---

## Client side framework

### Brief description

We currently have a bare-bones framework for communicating with urbit from a browser. It works reasonably well, but could easily be expanded to become more fully featured for developers. Our client-side applications have evolved to use the React / Flux framework, and we could improve our tooling to fit properly within that framework. 

One stretch goal for this project could include producing some developer tools to run in the browser. Imagine using emscripten to actually run vere inside a browser, or modifying browserify to run in the browser while pulling content from the urbit filesystem, `%clay`. 

### Difficulty

Medium to hard. Student would need solid JavaScript / CoffeeScript experience and would need to have communication skills for to engaging with the developer community. There's a lot of flexibility here depending on the student's background and experience.

### Mentor

Galen Wolfe-Pauly

---

## Native mobile application

### Brief description

Bringing a fundamental urbit application, such as `:talk`, to mobile would be a great project. With the annoucement of React Native and our reliance on React, it would be really exciting for us to try to have our existing client-side framework used natively. 

### Difficulty

Medium-hard. Student would need to have experience working on native mobile applications, preferably iOS. Design experience or interest would be a huge benefit here.

### Mentor

Galen Wolfe-Pauly

---

## Optimize the fsck out of our interpreter

### Brief description

We like to say that 'everything in urbit reduces to nock', and it does. Everything in urbit also runs in our interpreter, and we think it could be faster. A lot faster. There are a few potential strategies for this. One could include LLVM.

### Difficulty

Hard. This is pretty serious work, and the student would need to be either determined or simply have real technical chops.

### Mentor

Curtis Yarvin

---

## WebRTC for urbit

### Brief description

urbit could easily act as the broker for WebRTC connections. This would nicely compliment the communication tools we're building into urbit.

### Difficulty

Easy - medium. 

### Mentor

Galen Wolfe-Pauly

---

## Blob storage

### Brief description

urbit lives in memory and our filesystem `%clay` is strictly referentially transparent. This provides challenges for blob storage. There are a range of possible solutions to this problem. We have considered a few, and would be excited to work with a determined student interested in this problem. 

### Difficulty

Hard. The student would need to have a solid foundation of systems development. 

### Mentor

Curtis Yarvin

---

## You decide

### Brief description

If we all had personal cloud computers, what would they absolutely need? We try to ask ourselves that question quite a lot and want urbit to be simultaneously clean and concise and fully featured. If there's a project you would really like to implement on top of or as a part of urbit feel free to pitch it to us. 

### Difficulty

Hard. If you're going to propose something that's not on this list it should be substantial — but we're open to hearing any ideas you might have.

### Mentor

Curtis Yarvin or Galen Wolfe-Pauly depending on the project
