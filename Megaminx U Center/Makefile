.PHONY: all
all: Megaminx_UR_U_Center.log Megaminx_UFR_U_Center.log

Megaminx_UR_U_Center.log: Megaminx_UFR.tws Megaminx_U_Center.scr
	twsearch --moves U,R $^ | tee $@

Megaminx_UFR_U_Center.log: Megaminx_UFR.tws Megaminx_U_Center.scr
	twsearch $^ | tee $@
