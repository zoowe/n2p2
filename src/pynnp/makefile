#!/bin/make -f

pynnp:
	python setup.py build_ext --inplace
	cp pynnp.so ../../lib

clean:
	$(RM) pynnp.cpp pynnp.so
	$(RM) -r build
	$(RM) ../../lib/pynnp.so
