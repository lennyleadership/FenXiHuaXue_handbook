---
title = "Diagram demo"
description = ""
tags = [

]
date = "2022.08.09"
categories = [
]
menu = "main"
---

{{< mermaid >}}
stateDiagram-v2
    State1: The state with a note
    State1 --> State2
{{< /mermaid >}}


{{< mermaid >}}
stateDiagram
  direction LR

state1: Tailing Peaks 
state2: Sample
state3: solvent immiscibility
state4: Injector - malfunctioning valves?
state1 --> state2
state2 --> state3
state2 --> state4
{{< /mermaid >}}

{{< mermaid >}}
stateDiagram-v2
    [*] --> Active

    state Active {
        [*] --> NumLockOff
        NumLockOff --> NumLockOn : EvNumLockPressed
        NumLockOn --> NumLockOff : EvNumLockPressed
        --
        [*] --> CapsLockOff
        CapsLockOff --> CapsLockOn : EvCapsLockPressed
        CapsLockOn --> CapsLockOff : EvCapsLockPressed
        --
        [*] --> ScrollLockOff
        ScrollLockOff --> ScrollLockOn : EvScrollLockPressed
        ScrollLockOn --> ScrollLockOff : EvScrollLockPressed
    }
{{< /mermaid >}}


{{< mermaid >}}
stateDiagram-v2
    [*] --> A
    A --> B
    B --> C
    state B {
      a --> b
    }
    B --> D
{{< /mermaid >}}

