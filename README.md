# Fermat's Last Theorem for Exponent 3

A formalised proof of Fermat's Last Theorem for exponent 3 in the Lean proof assistant.

## Build Lean Files

To build the Lean files of this project, you need to have a working version of Lean.
See [the installation instructions](https://leanprover-community.github.io/get_started.html) (under Regular install).

To build the project, run `lake exe cache get` and then `lake build`.

## Build Blueprint

To build the web version of the blueprint, you need a working LaTeX installation.
Furthermore, you need some packages:

```
sudo apt install graphviz libgraphviz-dev
pip3 install invoke pandoc
cd .. # go to folder where you are happy clone git repos
git clone git@github.com:plastex/plastex
pip3 install ./plastex
git clone git@github.com:PatrickMassot/leanblueprint
pip3 install ./leanblueprint
cd sphere-eversion
```

To actually build the blueprint, run

```
lake exe cache get
lake build
inv all
```


## References

Hindry (2011) [Arithmetics](https://doi.org/10.1007/978-1-4471-2131-2). *Springer*.