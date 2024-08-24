# pong_flasing steps

# Fastboot Build -
1. Make sure to use latest platform tools
3. Reboot to bootloader 
2. If it's your first installation wipe data : fastboot -w 
3. Then flash rom - fastboot update --skip-reboot (drag and drop rom zip)
4. Flash custom recovery (optional)
5. Flash/sideload gapps (if vanilla build)
6. Sideload/flash FW (no need if already using latest)
6. boot

# Recovery Build - with custom recovery
1. Flash custom recovery and boot
2. Flash FW (no need if already using latest)
3. Flash Rom zip (If face error flash super_empty.img or try merge snapshot)
4. Clean cache (format data if coming from different rom)
5. Boot
