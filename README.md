# Clone
    git clone https://github.com/MrFluffyOven/ldcheck.git

# qseecomd
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/system/bin/qseecomd
# lib64
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/lib64/*
