# Deno By Example: Command-Line Arguments

Command-line arguments are a common way to parameterize execution of programs.

## The full source code:

```typescript
    for(let i = 0; i < Deno.args.length; i++) {
        let arg = Deno.args[i];
        console.log(`arg[${i}] = ${arg}`);
    }
```

## To run the example:
    deno run command-line-arguments.ts a b c d



