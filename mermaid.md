```mermaid
%%{ init: {'flowchart" : {'curve': 'step'}}}%%
flowchart TD
    A --> B{Is there any?}
    B --> C[/Input Yes/]
    B --> D[/Input No/]
    D --> E([END])
    C --> E 
```
