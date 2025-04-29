SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/dut.v
VERILOG_SOURCES += $(PWD)/../wrappers/dut_wrap.v
TOPLEVEL = dut_wrap
MODULE = dut_test
include $(shell cocotb-config --makefiles)/Makefile.sim
