# chibiDuino
chibiDuino pro ATmega8 38400 optiboot

atmega8o83.name=chibiDuino pro ATmega8 38400 optiboot

atmega8o83.upload.protocol=arduino
atmega8o83.upload.tool=avrdude
atmega8o83.upload.maximum_size=7680
atmega8o83.upload.speed=38400

atmega8o83.bootloader.tool=avrdude
atmega8o83.bootloader.low_fuses=0×94
atmega8o83.bootloader.high_fuses=0xDC
atmega8o83.bootloader.path=optiboot
atmega8o83.bootloader.file=optiboot_cp83.hex
atmega8o83.bootloader.unlock_bits=0×3F
atmega8o83.bootloader.lock_bits=0×0F

atmega8o83.build.mcu=atmega8
atmega8o83.build.f_cpu=8000000L
atmega8o83.build.core=arduino
atmega8o83.build.variant=standard
atmega8o83.build.board=AVR_ATMEGA8O83
