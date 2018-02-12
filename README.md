**1. Clone wallet sources**

```
git clone https://github.com/artocash/artowallet.git
```

**2. Create git submodule:**

```
git submodule add https://github.com/artocash/arto.git cryptonote
```

```
git submodule add https://github.com/fukuchi/libqrencode.git libqrencode
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```
