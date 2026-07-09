```mermaid
%%{ init: {'flowchart" : {'curve': 'stepAfter'}}}%%
flowchart TD
    A --> B {Is there any?}
    B --> C [/Input Yes/]
    B --> D [/Input No/]
    D --> E ([END])
    C --> E 
```