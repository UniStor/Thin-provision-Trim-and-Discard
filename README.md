# Thin-provision-Trim-and-Discard

## LVM
fstrim - guide: https://gist.github.com/hostberg/86bfaa81e50cc0666f1745e1897c0a56 discuss: https://www.reddit.com/r/linuxquestions/comments/qqh0mg/can_trim_be_used_to_reduce_lvm_thin_pool/

### Check if fstrim.timer enabled
code: `systemctl status fstrim.timer`

do: Make this run more Often! and execute it on demand when LVM Thin-pool is nearing full.
