####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS := util_mfifo_ip.tcl
M_DEPS += ../scripts/adi_env.tcl
M_DEPS += ../scripts/adi_ip.tcl
M_DEPS += ../common/ad_mem.v
M_DEPS += util_mfifo.v

M_VIVADO := vivado -mode batch -source

M_FLIST := *.cache
M_FLIST += *.data
M_FLIST += *.xpr
M_FLIST += *.log
M_FLIST += component.xml
M_FLIST += *.jou
M_FLIST +=  xgui
M_FLIST += .Xil



.PHONY: all clean clean-all
all: util_mfifo.xpr


clean:clean-all


clean-all:
	rm -rf $(M_FLIST)


util_mfifo.xpr: $(M_DEPS)
	rm -rf $(M_FLIST)
	$(M_VIVADO) util_mfifo_ip.tcl  >> util_mfifo_ip.log 2>&1

####################################################################################
####################################################################################
