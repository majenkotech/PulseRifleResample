RAW=click.raw glboom.raw glfire2.raw pr.raw pumpa.raw pumpb.raw pump_emptya.raw pump_emptyb.raw reload_ins.raw reload_rem.raw 

all: ${RAW}

%.raw: %.wav
	sox $< -r 22050 -c 1 $@

install: ${RAW}
	mv ${RAW} ../objects/

