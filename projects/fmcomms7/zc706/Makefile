####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS += system_top.v
M_DEPS += system_project.tcl
M_DEPS += system_constr.xdc
M_DEPS += system_bd.tcl
M_DEPS += ../common/fmcomms7_spi.v
M_DEPS += ../common/fmcomms7_bd.tcl
M_DEPS += ../../scripts/adi_project.tcl
M_DEPS += ../../scripts/adi_env.tcl
M_DEPS += ../../scripts/adi_board.tcl
M_DEPS += ../../common/zc706/zc706_system_plddr3_adcfifo.tcl
M_DEPS += ../../common/zc706/zc706_system_mig_constr.xdc
M_DEPS += ../../common/zc706/zc706_system_mig.prj
M_DEPS += ../../common/zc706/zc706_system_constr.xdc
M_DEPS += ../../common/zc706/zc706_system_bd.tcl
M_DEPS += ../../common/xilinx/sys_dacfifo.tcl
M_DEPS += ../../../library/xilinx/common/ad_iobuf.v
M_DEPS += ../../../library/axi_ad9144/axi_ad9144.xpr
M_DEPS += ../../../library/axi_ad9680/axi_ad9680.xpr
M_DEPS += ../../../library/xilinx/axi_adcfifo/axi_adcfifo.xpr
M_DEPS += ../../../library/xilinx/axi_adxcvr/axi_adxcvr.xpr
M_DEPS += ../../../library/axi_clkgen/axi_clkgen.xpr
M_DEPS += ../../../library/axi_dmac/axi_dmac.xpr
M_DEPS += ../../../library/axi_hdmi_tx/axi_hdmi_tx.xpr
M_DEPS += ../../../library/axi_spdif_tx/axi_spdif_tx.xpr
M_DEPS += ../../../library/xilinx/util_adxcvr/util_adxcvr.xpr
M_DEPS += ../../../library/util_cpack/util_cpack.xpr
M_DEPS += ../../../library/util_dacfifo/util_dacfifo.xpr
M_DEPS += ../../../library/util_upack/util_upack.xpr

M_VIVADO := vivado -mode batch -source

M_FLIST := *.cache
M_FLIST += *.data
M_FLIST += *.xpr
M_FLIST += *.log
M_FLIST += *.jou
M_FLIST +=  xgui
M_FLIST += *.runs
M_FLIST += *.srcs
M_FLIST += *.sdk
M_FLIST += *.hw
M_FLIST += *.sim
M_FLIST += .Xil
M_FLIST += *.ip_user_files



.PHONY: all lib clean clean-all
all: lib fmcomms7_zc706.sdk/system_top.hdf


clean: 
	rm -rf $(M_FLIST)


clean-all:clean
	make -C ../../../library/axi_ad9144 clean
	make -C ../../../library/axi_ad9680 clean
	make -C ../../../library/xilinx/axi_adcfifo clean
	make -C ../../../library/xilinx/axi_adxcvr clean
	make -C ../../../library/axi_clkgen clean
	make -C ../../../library/axi_dmac clean
	make -C ../../../library/axi_hdmi_tx clean
	make -C ../../../library/axi_spdif_tx clean
	make -C ../../../library/xilinx/util_adxcvr clean
	make -C ../../../library/util_cpack clean
	make -C ../../../library/util_dacfifo clean
	make -C ../../../library/util_upack clean


fmcomms7_zc706.sdk/system_top.hdf: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_VIVADO) system_project.tcl >> fmcomms7_zc706_vivado.log 2>&1


lib:
	make -C ../../../library/axi_ad9144
	make -C ../../../library/axi_ad9680
	make -C ../../../library/xilinx/axi_adcfifo
	make -C ../../../library/xilinx/axi_adxcvr
	make -C ../../../library/axi_clkgen
	make -C ../../../library/axi_dmac
	make -C ../../../library/axi_hdmi_tx
	make -C ../../../library/axi_spdif_tx
	make -C ../../../library/xilinx/util_adxcvr
	make -C ../../../library/util_cpack
	make -C ../../../library/util_dacfifo
	make -C ../../../library/util_upack

####################################################################################
####################################################################################
