_00_=.
_0D_=0D/python
das2jsondir=./0D/das2json
_STD_ = ${_0D_}/std

0D = ${_0D_}/gensym.py \
    ${_0D_}/datum.py \
    ${_0D_}/message.py \
    ${_0D_}/dynrouting.py \
    ${_0D_}/container.py \
    ${_0D_}/registry.py \
    ${_0D_}/process.py \
    ${_0D_}/0d.py \
    ${_STD_}/std.py \
    ${_STD_}/lib.py \
    ${_STD_}/fakepipe.py \
    ${_STD_}/transpiler.py \
    ${_STD_}/stock.py \
    ${_STD_}/run.py

D2J=${das2jsondir}/das2json

demo:
	@cat ${0D} main.py >py0d.py
	@$(D2J) empty.drawio
	@python3 py0d.py ${_00_} ${_0D_} "Hello World" main empty.drawio.json

clean:
	rm -rf empty.drawio.json
	rm -rf py0d.py
	rm -rf *~

install-js-requires:
	npm install yargs prompt-sync





