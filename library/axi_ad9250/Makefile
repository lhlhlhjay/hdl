####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS += ../common/ad_axi_ip_constr.xdc
M_DEPS += ../common/ad_datafmt.v
M_DEPS += ../common/ad_pnmon.v
M_DEPS += ../common/ad_rst.v
M_DEPS += ../common/ad_xcvr_rx_if.v
M_DEPS += ../common/up_adc_channel.v
M_DEPS += ../common/up_adc_common.v
M_DEPS += ../common/up_axi.v
M_DEPS += ../common/up_clock_mon.v
M_DEPS += ../common/up_xfer_cntrl.v
M_DEPS += ../common/up_xfer_status.v
M_DEPS += ../scripts/adi_env.tcl
M_DEPS += ../scripts/adi_ip.tcl
M_DEPS += axi_ad9250.v
M_DEPS += axi_ad9250_channel.v
M_DEPS += axi_ad9250_constr.xdc
M_DEPS += axi_ad9250_if.v
M_DEPS += axi_ad9250_ip.tcl
M_DEPS += axi_ad9250_pnmon.v

M_VIVADO := vivado -mode batch -source

M_FLIST := *.cache
M_FLIST += *.data
M_FLIST += *.xpr
M_FLIST += *.log
M_FLIST += component.xml
M_FLIST += *.jou
M_FLIST +=  xgui
M_FLIST += *.ip_user_files
M_FLIST += *.srcs
M_FLIST += *.hw
M_FLIST += *.sim
M_FLIST += .Xil



.PHONY: all clean clean-all
all: axi_ad9250.xpr


clean:clean-all


clean-all:
	rm -rf $(M_FLIST)


axi_ad9250.xpr: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_VIVADO) axi_ad9250_ip.tcl  >> axi_ad9250_ip.log 2>&1

####################################################################################
####################################################################################
