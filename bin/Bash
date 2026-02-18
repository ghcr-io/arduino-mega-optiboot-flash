git branch -m master Main
git fetch origin
git branch -u origin/Main Main
git remote set-head origin -a
avrdude -c stk500v2 -p m2560 -P COM5 -U flash:r:backup_firmware.hex:i
