#
# Makefile for MMC/SD card drivers
#

obj-$(CONFIG_MMC_BLOCK)		+= mmc_block.o panic_tranfer.o
mmc_block-objs			:= block.o queue.o
obj-$(CONFIG_MMC_TEST)		+= mmc_test.o

obj-$(CONFIG_SDIO_UART)		+= sdio_uart.o
# /* <DTS2010080901139 hufeng 20100821 begin */
obj-$(CONFIG_APANIC) += panic_tranfer.o
# /* DTS2010080901139 hufeng 20100821 end> */
