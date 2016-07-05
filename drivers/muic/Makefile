#
# Makefile for muic devices
#

obj-y					+= muic-core.o
obj-$(CONFIG_MUIC_NOTIFIER)		+= muic_notifier.o
obj-$(CONFIG_MUIC_FSA9480)		+= fsa9480.o
obj-$(CONFIG_MUIC_S2MM001)		+= s2mm001.o
obj-$(CONFIG_MUIC_SM5703)		+= sm5703-muic.o

# MUIC_UNIVERSAL
obj-$(CONFIG_MUIC_UNIVERSAL)	+= universal/
obj-$(CONFIG_MUIC_UNIVERSAL_SM5703)	+= universal/muic_regmap_sm5703.o
