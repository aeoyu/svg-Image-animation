# CPNT 201 Assignment 3 - SVG Image

---

**Author :** Filora

**Repo :** [Github Repo](https://github.com/aeoyu/cpnt201-a3)

**Site :** [Github Pages](https://aeoyu.github.io/cpnt201-a3/)

---

## Attribution / Links


[css animation for flashing glow](https://www.youtube.com/watch?v=A9_sGB2FLRA) copied code for the following code: (changed some of it's design)

```
animation-name: animate;
  animation-duration: 0.8s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}

@keyframes animate {
  0% {
    filter: drop-shadow(0px 0px 1px #fff)
    drop-shadow(0px 0px 3px #fff)
    drop-shadow(0px 0px 10px #ff80b3)
    drop-shadow(0px 0px 30px #ff4d94)
    drop-shadow(0px 0px 50px #ff0066);
  }

  100% {
    filter: drop-shadow(0px 0px 3px #fff)
    drop-shadow(0px 0px 6px #fff)
    drop-shadow(0px 0px 15px #ff80b3)
    drop-shadow(0px 0px 40px #ff4d94)
    drop-shadow(0px 0px 60px #ff0066); 
  }
}
```
