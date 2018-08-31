# Project Setup

- Create Empty VisualC++ project
- Go to project properties
    - Linker
        - System
            - set SubSystem to console
            - ![](2018-08-31-15-24-27.png)

- add Build Dependencies
- ![](2018-08-31-15-21-24.png)
  - Select masm
  - ![](2018-08-31-15-22-50.png)
- Go to .asm properties
    - Set Item Type to:
        - Microsoft Macro Assembler
    - ![](2018-08-31-15-27-49.png)
- If Error about safe Exception Handlers:
    - Go TO:
        - Linker
            - Advanced
                - Image Has Safe Exception Handlers > No
    - ![](2018-08-31-15-31-15.png)



