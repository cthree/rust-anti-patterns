# rust-anti-patterns
My curated list of anti-patterns, smells and bad practices for Rust code but many can be applied more broadly.

### Use a function argument to select between multiple code paths

This is commonly seen with `bool` or `Option<...>` arguments used in flow control expressions within the function body. For example:
