<div align="center">
   <h1> Shipooor 🚀 </h1>
</div>

<center> Ship Powerful code, Fast. Really, really fast with shipooor. </center>

## Snippets 🤓

### Anchor program snipppets
>`create context(cc)`
```rust
#[derive(Accounts)]
pub struct MyContext<'info> {

}
```
</br>

>`init pda(ipda)`
```rust
#[account(
    init, 
    payer = signer, 
    space = , 
    seeds = [], 
    bump,
)] 
pub new_account: Account<'info, NewAccount>,
```
</br>

>`create fn(cf)`
```rust
pub fn name(ctx: Context<Args>) -> Result<()> {
    Ok(())
}
```

</br>

>`create program(cp)`
```rust
#[program]
mod my_program {
    use super::*;
    pub fn init(ctx: Context<MyContext>) -> Result<()> {
        Ok(())
    }
}
```

Now It's time to be [explooorer](./snippets/rust-snippets.code-snippets)

### Anchor Client snipppets
>`new keypair (nk)`
```ts
const newKeypair =  anchor.web3.Keypair.generate();
```

>`new test case (ntc)`
```ts
it(" Some new test case", async () => { 
     
});
```

Now It's time to be [explooorer](./snippets/ts-snippets.code-snippets)


## Contribution

**Made in ❤️ with shipooor** - [0xDeep](https://twitter.com/0xDeep) & [Ache](https://twitter.com/acheroncrypto)
