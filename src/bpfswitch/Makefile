# SPDX-License-Identifier: GPL-2.0

SUBDIRS = ksrc usrc

all:
	@for s in $(SUBDIRS); do \
		make -C $$s $(BUILDDIR) all; \
	done

clean:
	@for s in $(SUBDIRS); do \
		make -C $$s $(BUILDDIR) clean; \
	done
