# Identicon

## Hashing

```elixir
hash = :crypto.hash(:md5, "banana")
Base.encode16(hash)

:binary.bin_to_list(hash)
```
