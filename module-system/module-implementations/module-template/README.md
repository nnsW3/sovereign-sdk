# This is a simple template for creating moules

It demonstrates the following concepts:

### 1. Module structure:

- `lib.rs` contains `ExampleModule` module definition and `sov_modules_api::Module` trait implementation for `ExampleModule`.
- `genesis.rs` contains the module initialization logic.
- `call.rs` contains methods that change module state in response to `CallMessage`.
- `query.rs` contains functions for querying the module state.

### 2. Functionality:

Anyone can update the value stored in the example module by sending a `CallMessage::SetValue(new_value)` message. Anyone can query the module state with `QueryMessage::GetValue` message.

Please, check comments in the `genesis.rs, call.rs & query.rs` for implementation details.