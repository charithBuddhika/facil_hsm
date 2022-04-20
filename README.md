# facil_hsm

Add following line to the facil.io CMakeLists.txt

```
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -pedantic -Wextra -Wwrite-strings -Wstrict-prototypes -Wmissing-prototypes -Wcast-qual -std=gnu11 -DPB_FIELD_16BIT")
```