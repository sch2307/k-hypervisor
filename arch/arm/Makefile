include ${SOURCE_PATH}/arch/arm/v7/Makefile

objs-y:=

objs-y += cp15.o
objs-y += cp15_64.o
objs-y += traps.o
objs-y += init.o
objs-y += irq.o
objs-y += lpae.o
objs-y += paging.o
objs-y += arch_regs.o
objs-y += fault.o
objs-y += psci.o
objs-y += smccc.o

obj-y += $(patsubst %, arch/arm/%, ${objs-y})

SUBDIRECTORIES += arch/arm/v7
