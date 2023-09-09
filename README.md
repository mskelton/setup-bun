# Setup Bun Action

Reduce boilerplate when setting up [Bun](https://bun.sh) and installing
dependencies.

## Usage

```yaml
- uses: mskelton/setup-bun@v1
```

## Checkout a specific Git ref

```yaml
- uses: mskelton/setup-bun@v1
  with:
   ref: ${{ github.head_ref }}
```

## Specify Bun version

```yaml
- uses: mskelton/setup-bun@v1
  with:
   bun-version: '1.0.0'
```

## Customize fetch depth

```yaml
- uses: mskelton/setup-bun@v1
  with:
   fetch-depth: 0
```

## Pass additional flags to the install command

```yaml
- uses: mskelton/setup-bun@v1
  with:
   flags: --production
```
