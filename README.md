# Clone
    git clone https://github.com/MrFluffyOven/ldcheck.git

# qseecomd (snapdragon)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/bin/qseecomd
# tzts (mtk/exynos)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/bin/tzts_daemon
# tz (mtk/exynos)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/bin/tzdaemon
# Keymint service (newer devices)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/bin/hw/android.hardware.security.keymint-service
# Gatekeeper service (all devices)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/bin/hw/android.hardware.gatekeeper@1.0-service
# Vaultkeeperd (samsung)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/bin/vaultkeeperd
# Vaultkeeper Service (samsung)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/bin/vendor.samsung.hardware.security.vaultkeeper@2.0-service
# sem daemon (samsung)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/system//bin/sem_daemon
# Gatekeeperd (all devices)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/system//bin/gatekeeperd
# lib64 (all devices)
    python3 ldcheck/ldcheck -p $OUT/recovery/root/system/lib64:$OUT/recovery/root/system/lib64/hw:$OUT/recovery/root/vendor/lib64:$OUT/recovery/root/vendor/lib64/hw -d $OUT/recovery/root/vendor/lib64/*
