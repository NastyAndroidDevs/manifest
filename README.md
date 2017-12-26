# Patches needed for bringup

Recommended to use repopick.

-----

### core

- 189546
- 189547
- 189548
- 189549
- 189550

### qcom display

- 188677

### system/bt

- 192528
- 192529

### frameworks/native

- 192580

### Copy - Paste
    repopick 189546
    repopick 189547
    repopick 189548
    repopick 189549
    repopick 189550

    repopick -f 188677

    repopick 192528
    repopick 192529

    repopick 192580
-----

# Extras

Not needed but nice to have

-----

### vendor/lineage

- 191330

### Copy - Paste
    repopick 191330

-----

Only use below if you are sure what you are doing

# KRYO

- kryo-libc

# ARMV8 32-BIT

- armv8-32bit
- https://android.googlesource.com/platform/external/skia/+/667a567f52cd00e809ade6e0f174772a768bb9a4

### Copy - Paste
    repopick -t kryo-libc
    repopick -f -t armv8-32bit

Need to pick external/skia manually

-----
