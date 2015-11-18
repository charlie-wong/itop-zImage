#
# Makefile for the linux kernel.
#

# Object file lists.

ifdef CONFIG_SMM6260_MODEM
        TAR_FILE="binary/smm6260_phone/itopeet_4x12/smm6260_phone.tgz"

exec := $(shell if [ -f $(TAR_FILE) ]; then tar -zxf $(TAR_FILE) -C $(src); fi )
endif

obj-$(CONFIG_SMM6260_MODEM) += smm6260_modem.o
