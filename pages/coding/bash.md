# Bash

* [BASH Programming - Introduction HOW-TO](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)


## Notes

### Arguments

* Compter les arguments

```
if [ $# -eq 0 ]; then
    echo "No arguments"
fi
```

* Tester qu'un argument est non vide

```
if [ -z "$1" ]; then
    echo "arg 1 is empty"
fi
```
