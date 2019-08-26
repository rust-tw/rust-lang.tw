# rust-lang.tw

## Local development

### 1. Install [Zola](https://www.getzola.org/)

```
cargo install --git https://github.com/getzola/zola
```

### 2. Launch dev server

```
zola serve
```

## Deploy

### 1. Install Now CLI

```
npm install -g now
```

### 2. Login

```
now login && now switch rust-tw
```

### 3. Deploy

```
now --prod
```
