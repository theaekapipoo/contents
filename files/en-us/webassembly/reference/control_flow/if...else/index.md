---
title: if...else
slug: WebAssembly/Reference/Control_flow/if...else
page-type: webassembly-instruction
---

{{WebAssemblySidebar}}

The **`if`** statement executes a statement if the last item on the stack is true (1). If the condition is false (0), another statement can be executed

{{EmbedInteractiveExample("pages/wat/if...else.html", "tabbed-taller")}}

## Syntax

```wasm
i32.const 0
(if
  (then
    ;; do something
  )
  (else
    ;; do something else
  )
)
```

| Instruction | Binary opcode |
| ----------- | ------------- |
| `if`        | `0x04`        |
| `else`      | `0x05`        |
